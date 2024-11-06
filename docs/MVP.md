 # **Terraformia MVP:**

* **Name:** Terraformia

* **Concept:** Procedural site generator using seed algorithms.

* **User Interaction:**

  + Command-line interface (CLI)

    - Accepts user input as seeds via CLI arguments.

      - Required argument: Seed (string or number)

      - Optional arguments:

        * Output directory (`--output`/`\-o`)

        * Site name (`--name`/`\-n`)

* **Key Features:**

1\. Generates a folder with user-provided site name containing the procedurally generated website based on seed input.

2\. Utilizes an algorithm seeded by user input to create:

+ Random directory structure (e.g., using Fractal Brownian Motion)

+ Variable file content and formatting (HTML, CSS, JavaScript) based on randomness derived from seed

3\. Does not include in-app editing capabilities for this MVP.

4\. Offers basic error handling and displays meaningful messages when errors occur.

**Goals for future iterations:**

1\. Develop a web UI to allow users to influence the site generator without directly editing code.

2\. Expand customization options for generated websites.

3\. Implement additional themes or templates for procedural generation.
