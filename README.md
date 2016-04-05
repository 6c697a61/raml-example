#raml-example
# to get this example running on an ec2 instance, make sure you have port 3000 open for incoming requests then do this:
sudo yum install nodejs npm --enablerepo=epel
npm install -g raml-server
npm install faker lodash
git clone git@github.com:6c697a61/raml-example.git
cd raml-example
raml-server api.raml

# test response:
curl http://localhost:3000/people

test statuses api enforce for admin
