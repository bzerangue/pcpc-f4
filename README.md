pcpc-f4
=======

PCPC Layout on Foundation 4

I started out by creating the foundation project with the following command

    compass create ./workspace -r zurb-foundation --using foundation  --sass-dir=sass --css-dir=css --javascripts-dir=js --images-dir=images

In the Foundation Sass files, I duplicated the `app.scss` and `_settings.scss` and renamed the files to `pcpc-f4.scss` and `_pcpc-f4-settings.scss`. I did this so when I upgrade Foundation in the future, my customizations will not be ovewritten. 

