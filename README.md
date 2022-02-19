Calculate images of magnetic-field-displaced spin-flip scattering—a Jupyter notebook approach

Adiabatic rotation of the neutron beam polarization from magnetization perpendicular to both the magnetic field applied to a sample and the scattering vector will displace the scattering relative to the unrotated neutron beam polarization.  The displacement is proportional to field and proportional to the square of neutron wavelength. For further information see <https://journals.aps.org/prb/abstract/10.1103/PhysRevB.73.134413> and references therein.

The code in the notebook will calculate and display images of the non-spin-flip and spin-flip scattering for a prescribed R(Q), where Q is the scattering vector (in Å-1) and R the ++, -- and spin-flip reflectivities.  An example of a real systems is provided (“LavesPhase.txt”).  The data are four tab-delimited columns (Q, R++, R--, RSF). 

In the “Experiment parameters” cell of the notebook, users provide the source frequency, mean value of neutron wavelength (in Å), initial and maximum field settings (Tesla) and the nominal scattering angle (in degrees) for the specular reflectivity.  The filename is set to the file of R(Q) data.  The calculation may incorporate a Maxwellian spectrum decay proportional to λ-5 (set to True) or not (set to False). The conditions provided in the notebook are appropriate for BL4A at SNS (ORNL).

The displacement of the spin-flip scattering from the non-spin-flip scattering is shown in the last cell.  The user can change the applied field using the B-slider bar.  Punching the “Reset” button will reset the field to the initial value. Use of B-slider may require require pip install ipywidgets and possibly pip install widgetsnbextension.

M.R. Fitzsimmons

18.02.22

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3968838.svg)](https://doi.org/10.5281/zenodo.6150619)

