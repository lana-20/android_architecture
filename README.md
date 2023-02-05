# [Android Skins](https://www.igyaan.in/178079/android-skins-different-companies/)

As an SDET Engineer, it is important to have a deep understanding of the various components that make up the Android operating system. 

<code>Android</code> is an open-source operating system, which:
- has it source code [publicly available](https://source.android.com/docs/setup/download/downloading) for use or redistribution 
- can be used as-is or “forked” and modified: (eg, [Fire OS](https://en.wikipedia.org/wiki/Fire_OS))
- is free but Google [may charge](https://www.theverge.com/2018/10/19/17999366/google-eu-android-licensing-terms) for Google Mobile Services (GMS), which include Google Play Store 
- runs on 2.5 billions devices as of May 2019 (eg, [Epson AR Headset](https://www.youtube.com/watch?v=1tvqsBwhCRw&ab_channel=RedrockBiometrics))

----

One key component of Android is the Hardware Abstraction Layer (HAL).

## [HAL](https://source.android.com/docs/core/architecture/hal)

<img width="700" src="https://user-images.githubusercontent.com/70295997/213611480-efb7f929-1119-482e-8a67-153981c2d303.png">

The <code>HAL</code> is a software layer that sits between the Android operating system and the device's hardware. It provides a standard interface for the operating system to interact with the device's hardware, and it abstracts the underlying hardware details so that the operating system does not need to be aware of them. This abstraction allows for the operating system to be more modular and easier to maintain, as it does not need to be updated for every new piece of hardware that is released.

<img width="1000" src="https://user-images.githubusercontent.com/70295997/213610583-27ba6b8f-1ce2-4cd1-93b1-d4542a6edbce.png">

⚙️ Dalvik vs ART ➡️ [Android Runtime (ART) and Dalvik](https://source.android.com/docs/core/runtime)

⚙️ Linux Kernel ➡️ [What is the Linux kernel?](https://www.redhat.com/en/topics/linux/what-is-the-linux-kernel)

- A common illustration of the Hardware Abstraction Layer (HAL) is to think of it as a "driver" for the operating system. Just as a driver allows a computer's operating system to communicate with a specific piece of hardware, such as a printer or a graphics card, the HAL allows the Android operating system to communicate with the device's hardware.

- Another way to illustrate HAL is to think of it as a translator, it translates the high-level commands from the Android operating system into low-level commands that the device's hardware can understand. The HAL acts as an intermediary between the operating system and the hardware, allowing the operating system to remain agnostic to the specific details of the hardware.

- A third illustration of HAL is to think of it as a bridge between the android os and the hardware. Just as a bridge connects two sides of a river, HAL connects the android os and the hardware. The android os sends requests and commands to the HAL, which then translates them into the specific commands that the hardware can understand and execute.

In short, the Hardware Abstraction Layer (HAL) is a crucial component of the Android operating system that allows the operating system to communicate with the device's hardware. It abstracts the underlying hardware details and provides a standard interface for the operating system, enabling it to be more modular and easier to maintain.

## ROM
Another important component is the <code>ROM</code> (Read-Only Memory) which refers to the firmware that controls the basic functions of a mobile device, such as its hardware and software interfaces. A ROM contains the instructions that tell a device how to boot up and operate, and it is stored in a non-volatile memory chip. Stock ROMs are the firmware that comes pre-installed on a device when it is manufactured, while custom ROMs are modified versions of the firmware that are created by third-party developers.

- A common illustration of a ROM (Read-Only Memory) is to think of it as the "brain" of a mobile device. Just as the brain controls and coordinates all the functions of the body, the ROM controls and coordinates all the functions of the mobile device. It contains the instructions that tell the device how to boot up and operate, and it is stored in a non-volatile memory chip.

- Another way to illustrate ROM is to think of it as the foundation of a building. Just as the foundation of a building provides the structural support and stability for the rest of the building, the ROM provides the basic functions and stability for the mobile device. Without a solid foundation, the building would not be able to stand, and without a solid ROM, the mobile device would not be able to function properly.

- A third illustration of ROM is to think of it as the map of a city. Just as a map shows the layout of a city and how to navigate it, the ROM shows the layout of the mobile device and how to navigate it. The ROM contains information about the device's hardware, software, and settings, and it tells the device how to use them.

In short, ROM (Read-Only Memory) is the firmware that controls the basic functions of a mobile device, such as its hardware and software interfaces. It contains the instructions that tell the device how to boot up and operate, and it is stored in a non-volatile memory chip. A solid and stable ROM is essential for the proper functioning of a mobile device.

## Skin
Finally, there is the <code>Skin</code>, also known as a firmware overlay or custom ROM, which is a custom version of the Android operating system that is installed on a mobile device. These skins are created by manufacturers, such as [Samsung](https://www.fastcompany.com/90264362/with-new-one-ui-samsung-shows-some-empathy-for-smartphone-users), LG, and OnePlus, and are designed to enhance the user experience and offer additional features and customization options.

- A common illustration of a Skin, also known as a firmware overlay or custom ROM, is to think of it as a "coat of paint" on a mobile device. Just as a coat of paint can change the appearance of a wall, a skin can change the appearance and features of a mobile device. Skins are created by manufacturers, such as Samsung, LG, and OnePlus, and are designed to enhance the user experience and offer additional features and customization options.

- Another way to illustrate a Skin is to think of it as a "custom suit" for a mobile device. Just as a custom suit is tailored to fit a person's specific measurements and preferences, a skin is tailored to fit a device's specific hardware and software. It can change the look, feel, and functionality of the device to suit the user's needs and preferences.

- A third illustration of a Skin is to think of it as a "themes" for a mobile device. Just as themes can change the appearance of a computer desktop, a skin can change the appearance and features of a mobile device. It can add new icons, new colors, new fonts, and new features to the device, making it more personalized and user-friendly.

In short, a Skin, also known as a firmware overlay or custom ROM, is a custom version of the Android operating system that is installed on a mobile device. These skins are created by manufacturers and designed to enhance the user experience and offer additional features and customization options. It can change the look and feel of the device, making it more personalized and user-friendly.

----

As an SDET Engineer, it is essential to understand how these different components interact with one another and how they can affect the overall performance and functionality of the device. This understanding is critical in developing and maintaining high-quality software and ensuring that it is compatible with a wide range of devices and hardware configurations.

<img width="800" src="https://user-images.githubusercontent.com/70295997/216799650-c44bd002-1a68-4a3e-b6a9-ac53a5308939.png">

<img src="https://user-images.githubusercontent.com/70295997/216799817-9dbbeab7-629b-4654-8a2f-bf51cc366776.png" width=40> Here are some examples of each component:

1. Hardware Abstraction Layer (HAL): the camera HAL provides a standard interface for accessing the camera hardware on a device, allowing the Android framework to take pictures, record videos, and adjust camera settings without having to know the specifics of the camera hardware.

2. Read-Only Memory (ROM): a custom ROM such as CyanogenMod provides a different operating system, user interface, and built-in apps than the original ROM installed on a device.

3. Dalvik: prior to Android 4.4, all Android devices used Dalvik as the virtual machine to run applications.

4. Android RunTime (ART): starting with Android 4.4, ART became the default virtual machine for running applications on Android devices, replacing Dalvik.

5. Skins: Samsung OneUI is a skin provided by Samsung that changes the look and feel of the user interface on Samsung devices. Another example is the custom ROM LineageOS, which provides its own skin, known as LineageOS Theme Engine.

----

<img src="https://user-images.githubusercontent.com/70295997/216799077-2d9e604c-c89e-4126-8cea-ea3e18ba3fe6.png" width=40> 

[More on Skins](https://github.com/lana-20/skins/tree/main#readme)

[More on HAL](https://github.com/lana-20/hal/blob/main/README.md)

[More on ART/Dalvik]()

[More on ROM](https://github.com/lana-20/rom/tree/main#readme)
