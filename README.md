# Multi-Dimens [![](https://jitpack.io/v/vimalcvs/multi-dimens.svg)](https://jitpack.io/#vimalcvs/multi-dimens)

Multi-Dimens is an Android library designed to facilitate responsive screen design across various device dimensions using a single layout file.

## Features

- **Responsive Design:** Create layouts that adapt to different screen sizes seamlessly.
- **Single Layout File:** Simplify your development process by managing multiple dimensions within a single layout file.
- **Flexible Usage:** Support for both normal size plus (dp) and font size (sp) dimensions.

## Installation

### Gradle

1. Add the JitPack repository to your project's build file.

```groovy
allprojects {
    repositories {
       ...
       maven { url 'https://jitpack.io' }
    }
}
```

2. Add the library dependency.

```groovy
dependencies {
    implementation 'com.github.vimalcvs:multi-dimens:1.1.1'
}
```

## Usage

### Dimension Types

The library supports the following dimension types:

- **Normal Size Plus (dp):** Use `@dimen/dp_` followed by the desired value.
- **Font Size (sp):** Use `@dimen/sp_` followed by the desired value.

### Example

To see how to use the Multi-Dimens library, refer to the [example layout](https://github.com/vimalcvs/multi-dimens/blob/main/app/src/main/res/layout/activity_main.xml) provided.

 

## Contribution

Your contributions are highly appreciated! If you find this library useful, consider starring it. You're also welcome to contribute by submitting pull requests or reporting any issues you encounter.

## License

This library is licensed under the MIT License. See the [LICENSE](https://github.com/vimalcvs/multi-dimens/blob/main/LICENSE) file for details.

## Acknowledgements

Special thanks to all contributors who have helped to improve this library.

---

🌟 If you find Multi-Dimens helpful in your projects, don't forget to give it a star! 🌟
