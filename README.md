### 👋

### Pull requests

### 2023

#### Responsive Images addon

I have been trusted and given repository admin access to [statamic-responsive-images addon](https://github.com/spatie/statamic-responsive-images) and I continue to contribute code to this addon. Additionally I now review other people's pull requests and manage opened issues.

Shipped a big breaking change update to the addon, which allows developers to customize responsive images dimensions output. https://github.com/spatie/statamic-responsive-images/pull/193

#### Statamic Focal Point Fieldtype addon

Created and published [my own little addon for Statamic](https://github.com/ncla/statamic-focal-point-fieldtype) which allows users to set focal point for an asset in a separate field, as currently in Statamic the focal point values are stored and tied to a single asset at a time.

### 2022

Participated in and completed Hacktoberfest 2022.

I have been contributing code quite a bit in the Statamic eco-system. While some of these PRs might appear simple, minimal on surface level, behind the scenes they required some code diving to understand what is going on.
- spatie/statamic-responsive-images#174 - Fix placeholder generation failing when changing `assets.image_manipulation.cache`
- spatie/statamic-responsive-images#173 - Fix `src` saving as an array and not as string
- statamic/cms#6854 - Preserve asset data from fields when running `statamic:assets:meta` generation command
- statamic/cms#6816 - Data list's toggle all button now selects maximum possible entries
- statamic/cms#6814 - Fix focal point not saving when asset blueprint has no fields
- spatie/statamic-responsive-images#164 - Fix required validation not working on the asset field
- spatie/statamic-responsive-images#156 - Do not update prop value directly; fix buggy dirty state prompt
- spatie/statamic-responsive-images#149 - Update all references to an asset if it get's renamed, deleted, moved
- spatie/statamic-responsive-images#145 - Fix focal focus not updating after changing it in control panel
- spatie/statamic-responsive-images#144 - Fix image `alt` attribute not being output from asset metadata
- spatie/statamic-responsive-images#123 - Add AVIF image support and quality settings control per breakpoint
- statamic/cms#5731 - Fix aspect ratio for control panel user avatar
