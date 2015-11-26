# Cartridge Specification
The purpose of this repository is to define the specification for a cartridge and to provide a base repository that can be used to create cartridges from.

## Stucture
A cartridge is broken down into the following sections:

 * infra
  * For infrastructure-related items
 * jenkins
  * For Jenkins-related items
 * src
  * For source control-related items

## Metadata
Each cartridge should contain a "metadata.cartridge" file that specifies the following metadata:

 * `CARTRIDGE_SDK_VERSION`
  * This defines the version of the Cartridge SDK that the cartridge conforms to
 
## Using this Repository
When developing a cartridge it is advisable to make a copy of this repository and remove all of the README.md files so that it may be used as a basis for the new cartridge.
