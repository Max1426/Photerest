# 第三方组件声明

Photerest 1.2.1 使用以下第三方运行时组件。Photerest 自有代码保持闭源，第三方组件的权利及义务分别由其许可证规定，不受 Photerest 专有许可中的限制覆盖。

## 项目及署名

- AndroidX / Jetpack（含 Compose、Material、Room、Lifecycle 等）：The Android Open Source Project 及贡献者。项目：https://android.googlesource.com/platform/frameworks/support/
- Kotlin 标准库：JetBrains s.r.o. 及 Kotlin 贡献者。项目：https://github.com/JetBrains/kotlin
- Kotlin Coroutines：JetBrains s.r.o. 及 Kotlin 贡献者。项目：https://github.com/Kotlin/kotlinx.coroutines
- JetBrains Java annotations：JetBrains s.r.o. 及贡献者。项目：https://github.com/JetBrains/java-annotations
- Guava ListenableFuture：Google 及 Guava 贡献者。项目：https://github.com/google/guava

上述组件均声明采用 Apache License 2.0。完整许可文本随本版本提供：[Apache-2.0.txt](licenses/Apache-2.0.txt)。这些第三方组件未由 Photerest 修改其源码；构建工具会进行正常的打包和编译处理。

## 本版本运行时依赖清单

清单根据 1.2.1 构建配置解析的 debugRuntimeClasspath 生成，并核对各组件 Maven POM（必要时包括父 POM）中的许可声明。包括传递依赖及该测试构建的 UI 测试清单辅助组件；不包含测试 APK、测试照片或测试脚本。

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
| `androidx.lifecycle:lifecycle-livedata-core:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-process:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-runtime-android:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-runtime-compose-android:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-runtime-ktx-android:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-viewmodel-android:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-viewmodel-ktx:2.8.6` | Apache-2.0 |
| `androidx.lifecycle:lifecycle-viewmodel-savedstate:2.8.6` | Apache-2.0 |
| `androidx.profileinstaller:profileinstaller:1.3.1` | Apache-2.0 |
| `androidx.room:room-common:2.6.1` | Apache-2.0 |
| `androidx.room:room-runtime:2.6.1` | Apache-2.0 |
| `androidx.savedstate:savedstate-ktx:1.2.1` | Apache-2.0 |
| `androidx.savedstate:savedstate:1.2.1` | Apache-2.0 |
| `androidx.sqlite:sqlite-framework:2.4.0` | Apache-2.0 |
| `androidx.sqlite:sqlite:2.4.0` | Apache-2.0 |
| `androidx.startup:startup-runtime:1.1.1` | Apache-2.0 |
| `androidx.tracing:tracing:1.0.0` | Apache-2.0 |
| `androidx.versionedparcelable:versionedparcelable:1.1.1` | Apache-2.0 |
| `com.google.guava:listenablefuture:1.0` | Apache-2.0 |
| `org.jetbrains.kotlin:kotlin-stdlib-jdk7:1.8.22` | Apache-2.0 |
| `org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.8.22` | Apache-2.0 |
| `org.jetbrains.kotlin:kotlin-stdlib:2.0.21` | Apache-2.0 |
| `org.jetbrains.kotlinx:kotlinx-coroutines-android:1.7.3` | Apache-2.0 |
| `org.jetbrains.kotlinx:kotlinx-coroutines-core-jvm:1.7.3` | Apache-2.0 |
| `org.jetbrains:annotations:23.0.0` | Apache-2.0 |
