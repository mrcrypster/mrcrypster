# Libs init
```
libroot=/var/apps/lib
git clone https://github.com/mrcrypster/mysqly.git $libroot/mysqly
git clone https://github.com/mrcrypster/phpy.git $libroot/phpy
git clone https://github.com/mrcrypster/clickhousy.git $libroot/clickhousy
```

# Update all libs
```
libroot=/var/apps/lib
for d in $libroot/*; do echo "Updating $d..."; git -C $d pull; done
```

# Creating app
```
php $libroot/phpy/phpy.php init /var/apps/projects
```
