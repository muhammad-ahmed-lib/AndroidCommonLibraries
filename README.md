
markdown
Copy
Edit
# 📦 Android Common Libraries Used

## 🛠 Core Libraries
implementation('androidx.core:core-ktx:1.12.0') \n
implementation('androidx.appcompat:appcompat:1.7.0')
implementation('com.google.android.material:material:1.12.0')
implementation('androidx.constraintlayout:constraintlayout:2.2.0')

shell
Copy
Edit

## 🧬 Lifecycle & ViewModel
implementation('androidx.lifecycle:lifecycle-runtime-ktx:2.8.7')
implementation('androidx.lifecycle:lifecycle-viewmodel-ktx:2.8.7')
implementation('androidx.lifecycle:lifecycle-livedata-ktx:2.8.7')
implementation('androidx.lifecycle:lifecycle-service:2.8.7')
implementation('androidx.lifecycle:lifecycle-extensions:2.2.0')

shell
Copy
Edit

## 🧪 Testing
testImplementation('junit:junit:4.13.2')
androidTestImplementation('androidx.test.ext:junit:1.2.1')
androidTestImplementation('androidx.test.espresso:espresso-core:3.6.1')

shell
Copy
Edit

## 🧭 Jetpack Compose
implementation(platform('androidx.compose:compose-bom:2024.04.01'))
implementation('androidx.compose.ui:ui')
implementation('androidx.compose.ui:ui-graphics')
implementation('androidx.compose.ui:ui-tooling-preview')
implementation('androidx.compose.material3:material3')
implementation('androidx.activity:activity-compose:1.10.0')
androidTestImplementation(platform('androidx.compose:compose-bom:2024.04.01'))
androidTestImplementation('androidx.compose.ui:ui-test-junit4')
debugImplementation('androidx.compose.ui:ui-tooling')
debugImplementation('androidx.compose.ui:ui-test-manifest')

shell
Copy
Edit

## 🧭 Navigation
implementation('androidx.navigation:navigation-fragment-ktx:2.8.4')
implementation('androidx.navigation:navigation-ui-ktx:2.8.4')

shell
Copy
Edit

## 🧩 Custom Modules
implementation(project(':customprogressbar'))
implementation(project(':numberpicker'))

shell
Copy
Edit

## 📏 SDP/SSP (Scalable size units)
implementation('com.intuit.sdp:sdp-android:1.1.1')
implementation('com.intuit.ssp:ssp-android:1.1.1')

shell
Copy
Edit

## 🖼 Image Loading - Glide
implementation('com.github.bumptech.glide:glide:4.16.0')

shell
Copy
Edit

## 💾 Room Database
implementation('androidx.room:room-runtime:2.6.1')
annotationProcessor('androidx.room:room-compiler:2.6.1')
kapt('androidx.room:room-compiler:2.6.1')
implementation('androidx.room:room-ktx:2.6.1')

shell
Copy
Edit

## 📸 CameraX
implementation('androidx.camera:camera-core:1.5.0-alpha03')
implementation('androidx.camera:camera-camera2:1.5.0-alpha03')
implementation('androidx.camera:camera-lifecycle:1.5.0-alpha03')
implementation('androidx.camera:camera-view:1.5.0-alpha03')

shell
Copy
Edit

## 🔍 ML Kit - Barcode Scanner
implementation('com.google.mlkit:barcode-scanning:17.0.3')

shell
Copy
Edit

## 🌐 Retrofit
implementation('com.squareup.retrofit2:retrofit:2.9.0')
implementation('com.squareup.retrofit2:converter-gson:2.9.0')

shell
Copy
Edit

## 🔥 Firebase
implementation('com.google.firebase:firebase-analytics:22.2.0')
implementation('com.google.firebase:firebase-crashlytics:19.4.0')

shell
Copy
Edit

## 📊 Charts - MPAndroidChart
implementation('com.github.PhilJay:MPAndroidChart:v3.1.0')

shell
Copy
Edit

## 🎞 Lottie Animations
implementation('com.airbnb.android:lottie:6.0.0')

shell
Copy
Edit

## 📢 Google AdMob
implementation('com.google.android.gms:play-services-ads:24.3.0')
