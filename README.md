# Toasty - Simple Toast Library

Toasty is a simple Toast library that allows you to display customizable toast messages in your Android application. This README provides step-by-step instructions on how to integrate Toasty into your project.

## Installation

### Step 1. Add the JitPack repository to your build file

Add the JitPack repository to your project-level `build.gradle` file:

```gradle
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}

```

### Step 2. Add the dependency

Add the Toasty dependency to your app-level build.gradle file:

```gradle
	implementation 'com.github.AppCodingPro:toasty2:1.0.0'
```
