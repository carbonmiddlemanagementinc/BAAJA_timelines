# BAAJA Project Timelines

An interactive comparison of federal permitting timelines for six representative energy projects (a gas pipeline, a geothermal plant, onshore wind, utility-scale solar, an interstate transmission line and Atlantic offshore wind) under current law and under the Bipartisan American Affordability and Jobs Act of 2026.

The whole page is one file, `index.html`. It has no build step and no dependencies beyond a Google Fonts stylesheet, and falls back to system fonts without it.

Last updated October 6, 2026. Reflects the bill text released September 30, 2026.

## Publish it with GitHub Pages

1. On github.com, create a new repository (for example, `baaja-timelines`). On a free GitHub account it must be **Public** for Pages to work.
2. In the new repository, click **Add file → Upload files**, drag in `index.html` and this `README.md`, and click **Commit changes**.
3. Go to **Settings → Pages** (under "Code and automation").
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the **main** branch and the **/ (root)** folder, and click **Save**.
5. After a minute or two, the page is live at `https://<your-username>.github.io/<repository-name>/`. The Pages settings screen shows the link once it is ready.

The published page is public: anyone with the address can see it.

## Updating it

Upload a new `index.html` to the same repository (Add file → Upload files, then commit). GitHub republishes it automatically, usually within a few minutes. Links to the page stay the same.

## Linking to a specific project

Add the project name after a `#` to open the page on that project, for example `.../#transmission`. The options are `pipeline`, `geothermal`, `wind`, `solar`, `transmission` and `offshore`.
