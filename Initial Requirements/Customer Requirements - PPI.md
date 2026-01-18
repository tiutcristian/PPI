# Customer Requirements

## Requirements

---

### Cases page

- Search + filters (ID, date, status), sortable table
- Status chips: Unsegmented / In progress / Segmented / Reported
- Open in viewer

### DICOM viewer

- Series list + thumbnails
- Axial scroll, MPR (coronal/sagittal),
- Window-Level presets (lung, mediastinal, bone), zoom/pan, reset
- Tools:
    - distance
    - angle
    - HU probe
    - rectangle/ellipse ROI
- Linked cursors across planes

### Results & explainability panel

- Biomarker list with confidence bars
- Toggle overlay: Heat-map**,**
- “Why?” drawer for feature-importance text

### Export

- Buttons: DICOM SEG, NIfTI, snapshot PNG, PDF report
- Download bundle (masks (segmentations) + metadata JSON)

### Work essentials

- Keyboard shortcuts
- Color-blind-safe palettes
- Crash recovery, like autosave
- keep author + timestamp

### Roles

- Login, role badge (Radiologist / Annotator / Admin)
- Read-only mode toggle for reviewers

### (Optional)

- PET/CT fusion with blend slider + SUV readouts
- Batch prefetch of priors, side-by-side comparison
- Built-in radiomics extract job → CSV download
- Multi-tenant support

## WORKFLOW

---

1. Ingest – New study arrives → case shows as Ready.
2. Triage – Open case from the Cases list (search/sort).
3. View — CT loads Adjust W/L, scroll,.
4. Segment — Paint Primary ****Tumor Autosave on (Later on)
5. Version & QA – Save → V1 created, reviewer approves or requests changes.
6. Export – DICOM SEG, NIfTI, snapshot PNG, optional PDF summary.
7. Close – Mark Reported/Exported, audit log updated.

## Similar Products

---

- [https://viewer.ohif.org/](https://viewer.ohif.org/)
- [https://www.slicer.org/](https://www.slicer.org/)
    - Mon AI label AI ADDON, with 3D slicer