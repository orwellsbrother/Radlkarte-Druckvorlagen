# Druck HowTo


## Project strucutre.

Fork or clone this repo and the radlkarte repo.

```bash
mkdir radlkarte-druck
cd radlkarte-druck
git clone https://github.com/orwellsbrother/Radlkarte-Druckvorlagen
git clone git@github.com:markusstraub/radlkarte.git

```


# Create new project.

Copy an existing project as a starting point.
You can then open this project in QGIS and reference the data in your radlkarte clone.

```bash
cd Radlkarte-Druckvorlagen
cp "Radlkarte Vorlage Bezirk BruckLeitha.qgz" "Radlkarte Vorlage MyGroup.qgz"
```


# Copy Layout Templates to Template Folder. 

These templates are a good starting point for creating a print layout.

```bash
cp layouts/* ~/.local/share/QGIS/QGIS3/profiles/default/composer_templates/
``` 
