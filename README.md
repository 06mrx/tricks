# tricks

# remove storage link
sudo find /usr/share/nginx/html/website/registrasi_ith/ -type l

unlink /usr/share/nginx/html/website/registrasi_ith/public/storage

# link to another laravel storage
sudo ln -s /usr/share/nginx/html/website/pmb_2022/storage/app/public /usr/share/nginx/html/website/registrasi_ith/public/storage 
