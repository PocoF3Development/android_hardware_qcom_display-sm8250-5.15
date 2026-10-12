# Alioth 5.15 display HAL development

Development only; not production ready or hardware boot validated.

This full-history fork accompanies the source-built alioth Linux 5.15 profile.
The DRM CSC logging call casts its signed coefficient to int64_t to match
PRId64 on both Android ABIs. Kernel UAPI layouts remain unchanged.
Use the pinned device kernel-5.15 manifest for the matching source set.
