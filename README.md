# results

1.  tmp_2c78d90

    * model: casesm; 
    * commit: 2c78d90; 
    * compset: FAMIPC5; 
    * resolution: fd14_fd14; 
    * levels: 35; 
    * time: 197901-198701
    * set:
    
···
      
      &phys_ctl_nl
        cam_chempkg            = 'trop_mam3'
        cam_physpkg            = 'cam5'
        conv_water_in_rad              =  1
        deep_scheme            = 'ZM'
        do_iss         =  .true.
        do_tms         =  .true.
        eddy_scheme            = 'diag_TKE'
        history_microphysics           =   .true.
        microp_scheme          = 'MG'
        shallow_scheme         = 'UW'
        srf_flux_avg           = 0
        tms_orocnst            =  1.0D0
        tms_z0fac              =  0.075D0
      ! ------------------------------
      ! cas-esm2 new schemes
      !============================================================
      ! deep_scheme        = 'ZYX1'      ! 'ZM'
      ! shallow_scheme     = 'ZW'        ! 'UW'
      ! macrop_scheme      = 'ZMH_WXC'   ! 'cam','WXC'
      ! microp_scheme      = 'M2M'       ! 'MG'
      ! eddy_scheme            = 'MTKE'      ! 'diag_TKE'
      ! ------------------------------
      ! in cas-esm1 schemes
      !============================================================
      ! deep_scheme        = 'ZM' ! 'ZM','ZYX1'
      ! shallow_scheme     = 'UW' ! 'UW','ZW'
      ! macrop_scheme      = 'cam'! 'cam' ZMH_WXC' ,'WXC'
      ! microp_scheme      = 'MG' ! 'MG','M2M'
      ! eddy_scheme        = 'diag_TKE'      ! 'diag_TKE','MTKE', 'HB','HBR'
      !============================================================
      /
      
  ···
      
      
    
    
      * diff with obs: https://czypku.github.io/cas-esm/l35/FAMIPC5/tmp_2c78d90/1979_1987/tmp_2c78d90-obs/


