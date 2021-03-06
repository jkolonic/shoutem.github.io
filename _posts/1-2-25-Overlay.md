---
layout: doc
permalink: /docs/ui-toolkit/components/overlay
title: Overlay
section: UI toolkit
---

# Overlay 

Overlay provides a convenient way to place content over Image, through semi-transparent background.

## Overlay
![alt text]({{ site.baseurl }}/img/ui-toolkit/tiles/large-tile@2x.png "Overlay"){:.docs-component-image}

#### JSX Declaration
```JSX
<Overlay styleName="...">
  {...}
</Overlay>
```
  

#### Style names

* **solid-light**: sets the text color to `Darker` variant, and the `backgroundColor` to `Background` variant, as defined in Theme
* **solid-dark**: sets the `backgroundColor` to `Darker` variant, while keeping the text color set to `Light` variant, as defined in Theme.
* **fill-parent**: sets the Overlay to fully fill parent container (without any margins, padding etc).

  