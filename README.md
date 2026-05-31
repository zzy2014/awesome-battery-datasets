# Awesome Battery Datasets

Curated collection of high-quality datasets for battery-related molecular and materials research, covering organic small molecules, molecular crystals, electrolyte mixtures, and polymers.

The repository focuses on datasets that include **physical properties relevant to energy storage**, such as conductivity, stability, solvation, redox potential, diffusion, and structural features.

---

# 📌 Dataset Categories

Datasets are organized by **material type**, rather than task, to better reflect chemistry and materials science workflows.

---

## 1. Organic Small Molecules

Datasets containing discrete organic molecules used in electrolytes, redox-active materials, and organic electrodes.

| Dataset | Collection Method | Size | Properties Included | Link |
|--------|------------------|------|---------------------|------|
| Dataset A | DFT + literature mining | 1.2M molecules | redox potential, HOMO/LUMO, dipole moment | [Link](#) |
| Dataset B | High-throughput computation | 500K molecules | stability, solvation energy, polarizability | [Link](#) |

### Typical Properties

- Redox potential
- HOMO / LUMO energy
- Dipole moment
- Solvation free energy
- Stability / decomposition energy

---

## 2. Molecular Crystals

Datasets of crystalline organic or inorganic molecular solids.

| Dataset | Collection Method | Size | Properties Included | Link |
|--------|------------------|------|---------------------|------|
| Dataset A | X-ray + DFT refinement | 100K crystals | lattice energy, band gap, density | [Link](#) |
| Dataset B | Crystal structure prediction (CSP) | 50K structures | stability, packing density | [Link](#) |

### Typical Properties

- Crystal structure (CIF)
- Lattice energy
- Band gap
- Density
- Mechanical stability
- Packing efficiency

---

## 3. Electrolyte Mixtures

Datasets of liquid electrolytes including solvents, salts, and additives.

| Dataset | Collection Method | Size | Properties Included | Link |
|--------|------------------|------|---------------------|------|
| Dataset A | MD simulation | 10K mixtures | ionic conductivity, viscosity | [Link](#) |
| Dataset B | Experimental + ML augmentation | 5K systems | diffusion coefficient, transference number | [Link](#) |

### Typical Properties

- Ionic conductivity
- Viscosity
- Diffusion coefficients
- Solvation structure
- Transference number
- Electrochemical stability window

---

## 4. Polymers

Datasets of polymer electrolytes, binders, and solid-state ion conductors.

| Dataset | Collection Method | Size | Properties Included | Link |
|--------|------------------|------|---------------------|------|
| Dataset A | MD simulation + experiments | 20K polymers | ionic conductivity, Tg, modulus | [Link](#) |
| Dataset B | High-throughput screening | 8K polymers | mechanical strength, ion mobility | [Link](#) |

### Typical Properties

- Ionic conductivity
- Glass transition temperature (Tg)
- Mechanical modulus
- Ion mobility
- Dielectric constant
- Electrochemical stability

---

# 📊 Standard Dataset Schema

Each dataset MUST follow this metadata format for consistency:

```yaml
name: Dataset Name
material_type: Organic / Crystal / Electrolyte / Polymer

collection_method:
  - DFT calculation
  - Molecular dynamics
  - Experimental measurement
  - Literature mining
  - High-throughput screening

size: Number of samples (e.g. 100K molecules)

representation:
  - SMILES
  - 3D coordinates
  - CIF (crystals)
  - Molecular graphs

properties:
  - list of physical / chemical properties included

data_format: CSV / JSON / HDF5 / ASE / CIF

temperature_range: optional
pressure_conditions: optional

license: open / restricted / academic
paper: link to publication (if available)
download: dataset URL
year: release year
