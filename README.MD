# Amazônia Legal Flags

Repository containing .png files for most of the cities of the Brazilian "Amazônia Legal" region (containing the states of Acre, Amapá, Amazonas, Maranhão, Mato Grosso, Pará, Rondônia, Roraima and Tocantins).

## Structure

The Flags are separated in folders named by the official state abbreviation code, and the file name is the IBGE code of the city.

## Sources

The source is primarily the CNM (Confederação Nacional de Municípios) public repository. I made a python script to capture the files in an automated way (getFlags.ipynb). There were a lot of flags missing after this first data capture, so I've gone to the Wikipedia page (e.g. https://commons.wikimedia.org/wiki/Flags_of_municipalities_of_Amazonas_(Brazil)) for each of the states' flags and manually downloaded (i could not find a way to get those flags per IBGE code or any consistent id in these pages) the ones that were missing from CNM and present in the Wikipedia repository. The ones who aren't in both repositories are as an empty .png file.

## Contributing

Feel free to send a pull request if you find a flag that is missing or wish to update a flag that you know has been replaced.