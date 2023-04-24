docker save -o laravel-it5.tar laravel-it5

docker load -i laravel-it5.tar

git remote add origin git@github.com:alborodin85/laravel-test-docker.git
git branch -M main
git push -u origin main


