# Variable-Stoichiometry
This is the file directory for the model code and controls pertaining to the simulation experiments performed in
"Variable Stoichiometry Effects on Glacial/Interglacial Ocean Model Biogeochemical Cycles and Carbon Storage"
by Nathaniel Fillman, Andreas Schmittner, and Karin Kvale.

Here is provided the mk.in and control.in files used to execute each simulation. Note, the control.in files for the
Tuned experiment are different from all others; these are located within the Tuned directory. The LGM and PI prefixes
denote for which climate state they are configured for.

The base code for the model (UVic and MOBI) is also provided while the "updates" directories under each experiment's
directory overrides the base code where needed.

The Control experiment is the fixed (for everything) stoichiometry configuration.
The VarPtN experiment adds a linearly variable P:N scheme to the Control configuration.
The VarSitN experiment adds a nonlinearly increasing Si:N scheme while retaining the variable P:N configuration
The Tuned experiment is no different from the VarSitN experiment except that the remineralization rate are increased.
     This is an initial attempt at tuning the model, although more is needed and will be completed in the future.

The file G_subgrid_bathy.nc is the recalculated LGM subgrid bathymetry used to reduce LGM sedimentary Fe fluxes.
