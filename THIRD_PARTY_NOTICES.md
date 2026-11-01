# Photerest 1.3.3 第三方声明

Photerest 自有代码闭源，允许免费安装和使用，见 LICENSE。以下第三方组件分别适用 Apache License 2.0，不受 Photerest 专有条款限制。完整许可文本见 licenses/Apache-2.0.txt。

AndroidX / Jetpack（含 WorkManager、Compose、Room、Lifecycle 等）：The Android Open Source Project 及贡献者，https://android.googlesource.com/platform/frameworks/support/ 。
Kotlin 标准库、Kotlin Coroutines 及 JetBrains annotations：JetBrains s.r.o. 及相应项目贡献者，https://github.com/JetBrains/kotlin 、https://github.com/Kotlin/kotlinx.coroutines 、https://github.com/JetBrains/java-annotations 。
Guava ListenableFuture：Google 及 Guava 贡献者，https://github.com/google/guava 。

清单按本版本实际 debugRuntimeClasspath 解析，并核对 Maven POM 或父 POM 的许可。第三方源码未修改，构建仅作正常编译打包。测试 APK 和测试照片不属于应用交付内容。

| 组件及版本 | 许可证 |
|---|---|
| `androidx.activity:activity-compose:1.9.3` | Apache-2.0 |
| `androidx.activity:activity-ktx:1.9.3` | Apache-2.0 |
| `androidx.activity:activity:1.9.3` | Apache-2.0 |
| `androidx.annotation:annotation-experimental:1.4.1` | Apache-2.0 |
| `androidx.annotation:annotation-jvm:1.8.1` | Apache-2.0 |
| `androidx.arch.core:core-common:2.2.0` | Apache-2.0 |
| `androidx.arch.core:core-runtime:2.2.0` | Apache-2.0 |
| `androidx.autofill:autofill:1.0.0` | Apache-2.0 |
| `androidx.collection:collection-jvm:1.4.4` | Apache-2.0 |
| `androidx.collection:collection-ktx:1.4.4` | Apache-2.0 |
| `androidx.compose.animation:animation-android:1.7.3` | Apache-2.0 |
| `androidx.compose.animation:animation-core-android:1.7.3` | Apache-2.0 |
| `androidx.compose.foundation:foundation-android:1.7.3` | Apache-2.0 |
| `androidx.compose.foundation:foundation-layout-android:1.7.3` | Apache-2.0 |
| `androidx.compose.material3:material3-android:1.3.0` | Apache-2.0 |
| `androidx.compose.material:material-icons-core-android:1.7.3` | Apache-2.0 |
| `androidx.compose.material:material-ripple-android:1.7.3` | Apache-2.0 |
| `androidx.compose.runtime:runtime-android:1.7.3` | Apache-2.0 |
| `androidx.compose.runtime:runtime-saveable-android:1.7.3` | Apache-2.0 |
| `androidx.compose.ui:ui-android:1.7.3` | Apache-2.0 |
| `androidx.compose.ui:ui-geometry-android:1.7.3` | Apache-2.0 |
| `androidx.compose.ui:ui-graphics-android:1.7.3` | Apache-2.0 |
| `androidx.compose.ui:ui-test-manifest:1.7.3` | Apache-2.0 |
| `androidx.compose.ui:ui-text-android:1.7.3` | Apache-2.0 |
| `androidx.compose.ui:ui-tooling-preview-android:1.7.3` | Apache-2.0 |
| `androidx.compose.ui:ui-unit-android:1.7.3` | Apache-2.0 |
| `androidx.compose.ui:ui-util-android:1.7.3` | Apache-2.0 |
| `androidx.concurrent:concurrent-futures-ktx:1.1.0` | Apache-2.0 |
| `androidx.concurrent:concurrent-futures:1.1.0` | Apache-2.0 |
| `androidx.core:core-ktx:1.13.1` | Apache-2.0 |
| `androidx.core:core:1.13.1` | Apache-2.0 |
| `androidx.customview:customview-poolingcontainer:1.0.0` | Apache-2.0 |
| `androidx.emoji2:emoji2:1.3.0` | Apache-2.0 |
| `androidx.exifinterface:exifinterface:1.3.6` | Apache-2.0 |
| `androidx.graphics:graphics-path:1.0.1` | Apache-2.0 |
| `androidx.interpolator:interpolator:1.0.0` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-common-java8:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-common-jvm:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-livedata-core-ktx:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-livedata-core:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-livedata:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-process:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-runtime-android:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-runtime-compose-android:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-runtime-ktx-android:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-service:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-viewmodel-android:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-viewmodel-ktx:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-viewmodel-savedstate:2.8.6` | Apache-2.0 |
| `androidx.profileinstaller:profileinstaller:1.3.1` | Apache-2.0 |
| `androidx.room:room-common:2.6.1` | Apache-2.0 |
| `androidx.room:room-ktx:2.6.1` | Apache-2.0 |
| `androidx.room:room-runtime:2.6.1` | Apache-2.0 |
| `androidx.savedstate:savedstate-ktx:1.2.1` | Apache-2.0 |
| `androidx.savedstate:savedstate:1.2.1` | Apache-2.0 |
| `androidx.sqlite:sqlite-framework:2.4.0` | Apache-2.0 |
| `androidx.sqlite:sqlite:2.4.0` | Apache-2.0 |
| `androidx.startup:startup-runtime:1.1.1` | Apache-2.0 |
| `androidx.tracing:tracing-ktx:1.2.0` | Apache-2.0 |
| `androidx.tracing:tracing:1.2.0` | Apache-2.0 |
| `androidx.versionedparcelable:versionedparcelable:1.1.1` | Apache-2.0 |
| `androidx.work:work-runtime-ktx:2.10.5` | Apache-2.0 |
| `androidx.work:work-runtime:2.10.5` | Apache-2.0 |
| `com.google.guava:listenablefuture:1.0` | Apache-2.0 |
| `org.jetbrains.kotlin:kotlin-stdlib-jdk7:1.8.22` | Apache-2.0 |
| `org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.8.22` | Apache-2.0 |
| `org.jetbrains.kotlin:kotlin-stdlib:2.0.21` | Apache-2.0 |
| `org.jetbrains.kotlinx:kotlinx-coroutines-android:1.7.3` | Apache-2.0 |
| `org.jetbrains.kotlinx:kotlinx-coroutines-core-jvm:1.7.3` | Apache-2.0 |
| `org.jetbrains:annotations:23.0.0` | Apache-2.0 |
