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
 <img src = "http://s1.postimg.org/6iaq5vxbz/Untitled.png"</img>
 
 
License
====
Copyright 2015 Cüneyt Çarıkçi,Serhat Sürgüveç

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
