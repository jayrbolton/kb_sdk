Known dependencies for testing kb_sdk itself (not modules) listed below. Please add more if discovered.

Must force RPC::Any, Moose updates cause XML tests to fail.

New versions of paramiko complain about being unable to import SSH2_AGENTC_REQUEST_IDENTITIES, 1.10.2 works.

With the new auth2 clients and server we may no longer need rsa, paramiko, Crypt::OpenSSL::RSA, Convert::PEM

Make sure nose2 is using python2.

pip install requests nose2 jsonrpcbase rsa paramiko==1.10.2

cpan Moose

cpan -f -i RPC::Any

cpan Bio::KBase::Exceptions

cpan Parse::Yapp Devel::StackTrace Lingua::EN::Inflect Template File::Slurp Cwd JSON Data::UUID XML::Dumper JSON::RPC::Client Exception::Class Config::Simple Digest::SHA1 Crypt::OpenSSL::RSA Convert::PEM DateTime MIME::Base64 URI Object::Tiny::RW Plack File::ShareDir::Install YAML TAP::Harness Plack::Middleware::CrossOrigin RPC::Any::Server::JSONRPC::PSGI

CasperJS must be installed, > 1.1.0. http://casperjs.org/ .  PhantomJS 1.9.x also required
