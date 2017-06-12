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
 <img src = "http://s1.postimg.org/6iaq5vxbz/Untitled.png"/>
 
Credits
====
<a href = "https://plus.google.com/u/0/116948443141721480957"><img src = "https://raw.githubusercontent.com/florent37/DaVinci/master/mobile/src/main/res/drawable-hdpi/gplus.png"/></a>
<a href = "https://twitter.com/Cuneyt_Carikci"><img src = "https://raw.githubusercontent.com/florent37/DaVinci/master/mobile/src/main/res/drawable-hdpi/twitter.png"/></a>
<a href = "https://www.linkedin.com/in/c%C3%BCneyt-%C3%A7ar%C4%B1k%C3%A7i-b4619161?trk=nav_responsive_tab_profile_pic"><img src = "https://raw.githubusercontent.com/florent37/DaVinci/master/mobile/src/main/res/drawable-hdpi/linkedin.png"/></a>

 
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
