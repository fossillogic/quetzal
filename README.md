# **Quetzal by Fossil Logic**

Quetzal is the intelligent tool for managing Fossil Logic’s AI/Truthful Intelligence (TI) systems. It unifies telemetry, dataset validation, model testing, and host awareness, providing a single CLI for all AI operational needs.
Key Subcommands: telemetry (host and system telemetry), dataset (validate and inspect datasets), validate (model validation), awareness (system awareness for TI), test (run structured AI tests).

## **Prerequisites**

Ensure you have the following installed before starting:

- **Meson Build System**: This project relies on Meson. For installation instructions, visit the official [Meson website](https://mesonbuild.com/Getting-meson.html).

## **Setting Up Meson Build**

1. **Install Meson**:
    - Follow the installation guide on the [Meson website](https://mesonbuild.com/Getting-meson.html) for your operating system.

## **Setting Up, Compiling, Installing, and Running the Project**

1. **Clone the Repository**:

    ```sh
    git clone https://github.com/fossillogic/quetzal.git
    cd quetzal
    ```

2. **Configure the Build**:

    ```sh
    meson setup builddir
    ```

3. **Compile the Project**:

    ```sh
    meson compile -C builddir
    ```

4. **Install the Project**:

    ```sh
    meson install -C builddir
    ```

5. **Run the Project**:

    ```sh
    quetzal
    ```

## **Contributing**

Interested in contributing? Please open pull requests or create issues on the [GitHub repository](https://github.com/fossillogic/quetzal).

## **Feedback and Support**

For issues, questions, or feedback, open an issue on the [GitHub repository](https://github.com/fossillogic/quetzal/issues).

## **License**

This project is licensed under the [Mozilla Public License](LICENSE).
