# collection-experience-core

The shared, reusable components of two public installations that open up a collection as an interactive
cloud or timeline: the **Collection Wall OpenStack 2.0** in the
[TU Delft Library](https://www.tudelft.nl/en/library/visit/relax-and-get-inspired/collection-wall-at-the-tu-delft-library)
and **Van muziekbibliotheek naar publieksbeleving** in [Fonos](https://fonos.nl), the new
music location of Beeld & Geluid in Hilversum. Both projects build on this one open framework; a new
collection is a new profile and data bundle, not new software.

> **Status:** under construction. The components are developed in TangibleApp's workshop and published here
> regularly; the first publication follows shortly.

## What it will contain

| Part | What |
|---|---|
| Core | the data bundle format and the provider interfaces (similarity, layout, search, import) |
| Processing | open providers: text and image vectors, similarity, layouts |
| Journey | the interaction core (camera, selection, search), free of any UI framework |
| Explorer | a .NET/Skia presentation; TouchDesigner modules for the wall |
| Importers | from a catalogue or API to a data bundle |
| Sensor services | touch through the glass (lidar), presence (radar), arm gestures (3D lidar): one open OSC contract, no camera images |
| Operations | telemetry contract, monitoring, deployment |

## Branches and releases

`main` is the released state, with a tagged release per milestone; `next` is the work in progress, also
public. Installations follow `main`.

## Licence

Source code under the MIT licence ([LICENSE](LICENSE)); all project results are also available under
CC BY 4.0 ([LICENSE-CC-BY-4.0.md](LICENSE-CC-BY-4.0.md)). Collection content is not part of this repository.

## Related

- [collection-wall-tudelft](https://github.com/immersive-library-experience/collection-wall-tudelft): the TU Delft Library installation
- [collectiegebouw-muziek-in-context](https://github.com/immersive-library-experience/collectiegebouw-muziek-in-context): the Beeld & Geluid installation
- [lab](https://github.com/immersive-library-experience/lab): experiments and proofs of concept

Developed by TangibleApp with Trebla Technology, for TU Delft Library and Beeld & Geluid.

## Funding

Dit project is tot stand gekomen met steun van Stichting Pica. Stichting Pica bevordert de wetenschappelijke en openbare informatievoorziening, onder andere door projecten te financieren. Meer informatie over Stichting Pica vind je op www.stichtingpica.nl.

This project was made possible with support from Stichting Pica, which advances scientific and public information provision, among other things by funding projects (www.stichtingpica.nl).
