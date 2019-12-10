docker build . (pegar id da imagem)
gcloud auth configure-docker
docker tag id_imagem gcr.io/$(gcloud config get-value project)/appbasico:latest
docker push gcr.io/rails-lab-260819/appbasico:latest


postgresql://postgres:senha@10.19.144.3/db-prod
sudo kubectl apply -f deploy/job.yml

 sudo kubectl delete jobs/db-migrate


 teste
