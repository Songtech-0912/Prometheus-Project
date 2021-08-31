# Prometheus Project

 Bringing Linux applications to every Linux distribution.

⚠: The project will be put on hold for a few months due to personal schedule conflicts. 

## About the Project

The goal of this project is to make Linux more accessible by creating *appimages* of as many apps as possible. An `appimage` is a universal linux packaging format that reduces the need for each distro to have a separate package. Appimages are fast, convienient, and secure.

However, less well known Linux apps often don't have the luxury of being packaged as appimages, and because of this, they only run on a few platforms, or have to be built from source, which discourages many users. If these apps could be packaged as appimages, they would be more accessible, and they might gain more exposure and become more well-known. That is exactly what this project aims to do.

## Project Goals

The Prometheus Project's most fundamental goal is to *bring Linux applications to every Linux distribution through AppImages*. To achieve this, it has four secondary goals:

- Create a *freedom-respecting*, *transparent* and *reproducible* method of packaging AppImages from software source code, as well as making it easy for developers already using other build tools to make AppImages
- Create *reliable* and *simple* ways of installing AppImages, for everyone from novices to experienced Linux users
- Create a desktop app store for AppImages that interfaces with the Prometheus Project and handles installation, uninstallation, and updating of AppImages for the user
- Present a *user-friendly* introduction to AppImage technology, throught the Prometheus website, documentation, and community hub
- Allow for developers to monetize their apps through the Prometheus app store while keeping all of the applications free and open-source

## Getting Started

### 1. Learn how to make an AppImage

Information on packaging appimages is available in the [docs](./docs/Introduction.md). 

### 2. Try out an AppImage

The list of AppImages is constantly growing. Currently, I've packaged these apps as appimages:

* Blender

    * Blender 2.83: get it [here](https://github.com/Songtech-0912/Prometheus-Project/releases/tag/v1.0-beta)

    * Blender 2.90 (beta): get it [here](https://github.com/Songtech-0912/Prometheus-Project/releases/tag/v1.0-beta)

* Instant Meshes: get it [here](https://github.com/Songtech-0912/Prometheus-Project/releases/tag/v1.0-beta.2)

Alternatively, you may also download these appimages on [AppImageHub](https://www.appimagehub.com/). For the links to each AppImage hosted on AppImageHub, see [publish-list.md](publish-list.md).

### 3. Give feedback about AppImages

Any feedback about how well the AppImages here perform would be greatly appreciated. You can open an [issue](https://github.com/Songtech-0912/Prometheus-Project/issues) or take [this survey](https://yuxuansong419407.typeform.com/to/f09PivNq)  to give feedback.

## FAQ

### Q: Why AppImages and not static portable binaries?

Static portable binaries have issues updating, do not integrate well into a desktop (as they don't add file associations, app icons, file format icons, etc.), and are far more meant for development builds than production-ready software.

### Q: What is the relationship between this project and AppImagehub?

This project is intended to both complement and support AppImageHub. Seriously, this is a passion project, AppImagehub is a professional foundation for furthering AppImage development.

### Q: I don't like AppImages! They bloat my computer!

While it is true that AppImages can pack a large number of dependencies with them and thus cause excessive duplicated libraries across your system, we are constantly working on improving AppImage performance and reducing AppImage size.

### Q: Do you accept donations?

Maybe, in the future, but right now there are far more needy and pressing causes to donate to. Donate to another developer and charity instead, not me.

## Roadmap

I will continue making the Prometheus Project better, and that means I'm working on these things at the moment:

- Python scripts that will be able to handle the AppImage creation process and uploading process automatically
- GitHub Actions integration to automatically upload the python-generated AppImages
- A proper website for downloading the AppImages, giving feedback, etc.
- A script that will mirror these appimages to AppImageHub
- Proper docs for the Prometheus Project, with detailed instructions on how to build AppImages, troubleshooting AppImage errors, etc.
- Adding backward compatibility for AppImages
- A true 1.0 stable release instead of countless pre-releases

## Thanks

This project couldn't have been possible without the hard work of these amazing people. Please consider donating to them to support their projects.

* Developers of [AppImage](https://appimage.org/)
* Developers of [Blender](https://www.blender.org/) 
* Developers of [Instant Meshes](https://github.com/wjakob/instant-meshes)
* Developers of [Ardour](https://ardour.org)
