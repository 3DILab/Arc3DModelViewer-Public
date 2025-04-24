# Arc 3D Model Viewer

While the project is currently not open source, this git will serve as a public issue tracker for Arc 3D Model Viewer https://www.rchsd.org/programs-services/3d-innovations-lab/research-projects/arc3dmodelviewer/

Please report any bugs you encounter and feel free to add any feature requests.

Version 1.3.0 released on 28 Feb 2025

	• Updated error reporting when importing an invalid model.
	• Updated layout for help window to support additional tutorials.
	• Fixed crash which can result from rotating the camera based on the mouse position while the clipping plane is active.
	• Fixed axis indicator not being hidden under certain conditions.
	• Fixed progress tracker prematurely disappearing when loading models in batches.
 
Version 1.2.0 released on 4 Feb 2025

	• Added instancing system toggle, allowing models opened through file association to be imported into an already open instance of the viewer.
	• Added drag-and-drop file importing.
	• Added "delete" hotkey for removing selected models and parts from the viewer.
	• Added option to rotate camera around the mouse's starting position on the model. This is off by default.
	• Updated application icon and updated copyright information.
	• Fixed initial orientation of imported models to be consistent with global coordinate system of source files.
	• Fixed update checker not checking for updates consistently.
	• Fixed names and materials not loading correctly when several 3MF files are batch imported.
	• Fixed preset colors not loading correctly for compatible STL files.

Version 1.1.0 released on 10 Oct 2024.

	• Added 3MF support (Core Specification support with limited support for the Material and Properties extension).
	• Added glTF (.gltf and .glb) support including support for glTF Draco.
	• Added option in the settings menu to cap the framerate. Default is set to 30 FPS.
	• Added code signing to installer (this should reduce Microsoft SmartScreen warnings during installation for most users).
	• Added support for object names in OBJ files.
	• Added group selection to removal tool.
	• Added support for part removal
	• Updated camera to improve support for small models.
	• Fixed transparency and clipping slider breaking in some situations.
	• Fixed support for RecommendedDisplayCIELabValue in DICOM-Encapsulated STLs.
	• Fixed models sometimes shifting when merging and splitting parts.
 	• Fixed initial camera orientation for X3D models.
