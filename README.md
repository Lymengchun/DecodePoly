# DecodePoly Library
 >Step 1. Add the JitPack repository to your build file
 ```Add it in your root build.gradle at the end of repositories:
 allprojects {
 
  repositories {
	...
	maven { url 'https://jitpack.io' }
  }
	
}
 ```
 
 > Step 2. Add the dependency to gradle
 ```gradle
 dependencies {

	implementation 'com.github.Lymengchun:DecodePoly:1.0.0'

 }
  ```
  
   > Step 3. Implement
 ```
 DecodePoly decodePoly = new DecodePoly();

 ArrayList<LatLng> puntos = decodePoly.decodePoly("_izlhA~pvydF_{geC~{mZ_kwzCn`{nI");

 Log.d("Demo", "polyline list:"+puntos);
 
 result: polyline list:[lat/lng: (90.0,-125.0), lat/lng: (90.0,-129.5), lat/lng: (90.0,175.47000000000003)]

  ```
  


