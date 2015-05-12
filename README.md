# Simple-Image-Blur
Simple image blurring for android

Usage
====
For imageView 

        imageview = (ImageView) itemView.findViewById(R.id.imageView);

        BitmapDrawable drawable = (BitmapDrawable) imageview.getDrawable();
        Bitmap bitmap = drawable.getBitmap();
        Bitmap blurred = blurRenderScript(bitmap, radiusArr[position]);//second parametre is radius
        imageview.setImageBitmap(blurred);        




SS
====
 <img src = "http://i.imgur.com/iOv7aEo.png"</img>
