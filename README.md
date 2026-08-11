plugins {
    id 'com.android.application'
}

android {
    namespace 'com.priyaai.app'
    compileSdk 35

    defaultConfig {
        applicationId 'com.priyaai.app'
        minSdk 24
        targetSdk 35
        versionCode 1
        versionName '1.0'
    }
}

dependencies {
    implementation 'androidx.appcompat:appcompat:1.7.0'
    implementation 'com.google.android.material:material:1.12.0'
}
