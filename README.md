docker image build -t {nomeDaImage} .

docker run -p 1935:1935 -p 8080:8080 {nomeDaImage}