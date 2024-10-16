# Install

```
rigel@rigel-Latitude-E6520:~/alice$ aliBuild init O2Physics@master

==> In order to improve user experience, aliBuild would like to gather analytics about your builds.
    You can find all the details at:
    
      https://github.com/alisw/alibuild/blob/master/ANALYTICS.md
    
Is that ok for you [YES/no]? yes

==> Development directory . created for o2physics
rigel@rigel-Latitude-E6520:~/alice$ ls
alidist  O2Physics  sw
rigel@rigel-Latitude-E6520:~/alice$ aliBuild build O2Physics

==> Packages will be built in the following order:
     - alibuild-recipe-tools@v0.2.5
     - GCC-Toolchain@v13.2.0-alice1
     - Alice-GRID-Utils@0.0.7
     - O2-customization@v1.0.0
     - MLModels@20220530
     - Python-modules-list@1.0
     - AliEn-CAs@f62625ede780d455b3b7878064bcfee6bd9a4f53
     - ITSResponse@v1.0.0
     - lzma@v5.2.3
     - UUID@alice/v2.27.1
     - zlib@v1.2.8
     - lhapdf@v6.5.2
     - GMP@v6.2.1
     - libtirpc@libtirpc-1-1-4
     - GSL@release-1-16
     - libffi@v3.2.1
     - bz2@8ca1faa31f396d94ab927b257f3a05236c84e330
     - libxml2@v2.9.3
     - FreeType@VER-2-10-1
     - OpenSSL@OpenSSL_1_1_1m
     - MPFR@v3.1.3
     - ApMon-CPP@v2.2.8-alice6
     - CMake@v3.28.1
     - AliEn-Runtime@v2-19-le
     - json-c@json-c-0.17-20230812
     - c-ares@cares-1_18_1
     - utf8proc@v2.6.1
     - FFTW3@v3.3.9
     - ms_gsl@v4.0.0
     - pythia6@428-alice2
     - protobuf@v21.9
     - hdf5@hdf5-1_10_9
     - curl@curl-7_70_0
     - FairCMakeModules@v1.0.0
     - libuv@v1.40.0
     - lz4@v1.9.3
     - GLFW@3.3.2
     - re2@2019-09-01
     - HepMC@HEPMC_02_06_10
     - ninja@v1.11.1.g95dee.kitware.jobserver-1
     - libpng@v1.6.34
     - double-conversion@v3.1.5
     - TBB@v2021.5.0
     - abseil@20220623.1
     - libjalienO2@0.1.4
     - sqlite@v3.15.0
     - googlebenchmark@v1.6.1
     - xercesc@v3.2.5
     - fmt@10.1.1
     - Vc@1.4.1
     - libwebsockets@v4.3.2
     - flatbuffers@v24.3.25
     - ZeroMQ@v4.3.5
     - Clang@llvmorg-18.1.8-alice2
     - DebugGUI@v0.8.0
     - RapidJSON@091de040edb3355dcf2f4a18c425aec51b906f08
     - grpc@v1.50.1
     - Python@v3.9.16
     - GEANT4@v11.2.0
     - FairLogger@v1.11.1
     - VecGeom@v1.2.6
     - xsimd@8.1.0
     - bookkeeping-api@@aliceo2/bookkeeping@0.93.0
     - Python-modules@1.0
     - XRootD@v5.7.0
     - boost@v1.83.0-alice2
     - xjalienfs@1.6.3
     - arrow@apache-arrow-17.0.0-alice6
     - Ppconsul@v0.2.3
     - pythia@v8311
     - Common-O2@v1.6.3
     - FairMQ@v1.8.4
     - cgal@4.12.2
     - libInfoLogger@v2.7.3
     - ONNXRuntime@v1.18.1
     - Configuration@v2.8.0
     - ROOT@v6-32-06-alice1
     - generators@vAN-20210812
     - fastjet@v3.4.1_1.052-alice2
     - Monitoring@v3.18.1
     - HepMC3@3.3.0
     - vgm@v5-3
     - KFParticle@alice/v1.1-5
     - JAliEn-ROOT@0.7.14
     - VMC@v2-0
     - MCStepLogger@v0.6.1
     - GEANT3@v4-4
     - GEANT4_VMC@v6-6-p1
     - simulation@v1.0
     - FairRoot@v18.4.9-alice3
     - O2@daily-20241015-0200
     - O2Physics (development package)

==> You have packages in development mode (O2Physics).
    This means their source code can be freely modified under:
    
      /home/rigel/alice/<package_name>
    
    aliBuild does not automatically update such packages to avoid work loss.
    In most cases this is achieved by doing in the package source directory:
    
      git pull --rebase
    
==> Updating repositories: done      
==> Downloading tarball for defaults-release@v1: done  
==> Unpacking defaults-release@v1: done
==> Downloading tarball for alibuild-recipe-tools@0.2.5: done  
==> Unpacking alibuild-recipe-tools@0.2.5: done
==> Downloading tarball for GCC-Toolchain@v13.2.0-alice1: done      
==> Unpacking GCC-Toolchain@v13.2.0-alice1: done
==> Downloading tarball for Alice-GRID-Utils@0.0.7: done  
==> Unpacking Alice-GRID-Utils@0.0.7: done
==> Downloading tarball for O2-customization@v1.0.0: done  
==> Unpacking O2-customization@v1.0.0: done
==> Downloading tarball for MLModels@20220530: done   
==> Unpacking MLModels@20220530: done
==> Downloading tarball for Python-modules-list@1.0: done  
==> Unpacking Python-modules-list@1.0: done
==> Downloading tarball for AliEn-CAs@v1: done   
==> Unpacking AliEn-CAs@v1: done
==> Downloading tarball for ITSResponse@v1.0.0: done     
==> Unpacking ITSResponse@v1.0.0: done
==> Downloading tarball for lzma@v5.2.3: done   
==> Unpacking lzma@v5.2.3: done
==> Downloading tarball for UUID@v2.27.1: done  
==> Unpacking UUID@v2.27.1: done
==> Downloading tarball for zlib@v1.2.8: done   
==> Unpacking zlib@v1.2.8: done
==> Downloading tarball for lhapdf@v6.5.2: done   
==> Unpacking lhapdf@v6.5.2: done
==> Downloading tarball for GMP@v6.2.1: done   
==> Unpacking GMP@v6.2.1: done
==> Downloading tarball for libtirpc@libtirpc-1-1-4: done   
==> Unpacking libtirpc@libtirpc-1-1-4: done
==> Downloading tarball for GSL@v1.16: done    
==> Unpacking GSL@v1.16: done
==> Downloading tarball for libffi@v3.2.1: done   
==> Unpacking libffi@v3.2.1: done
==> Downloading tarball for bz2@1.0.8: done   
==> Unpacking bz2@1.0.8: done
==> Downloading tarball for libxml2@v2.9.3: done    
==> Unpacking libxml2@v2.9.3: done
==> Downloading tarball for FreeType@v2.10.1: done      
==> Unpacking FreeType@v2.10.1: done
==> Downloading tarball for OpenSSL@v1.1.1m: done    
==> Unpacking OpenSSL@v1.1.1m: done
==> Downloading tarball for MPFR@v3.1.3: done   
==> Unpacking MPFR@v3.1.3: done
==> Downloading tarball for ApMon-CPP@v2.2.8-alice6: done   
==> Unpacking ApMon-CPP@v2.2.8-alice6: done
==> Downloading tarball for CMake@v3.28.1: done      
==> Unpacking CMake@v3.28.1: done
==> Downloading tarball for AliEn-Runtime@v2-19-le: done      
==> Unpacking AliEn-Runtime@v2-19-le: done
==> Downloading tarball for json-c@v0.17.0: done   
==> Unpacking json-c@v0.17.0: done
==> Downloading tarball for c-ares@1.18.1: done   
==> Unpacking c-ares@1.18.1: done
==> Downloading tarball for utf8proc@v2.6.1: done   
==> Unpacking utf8proc@v2.6.1: done
==> Downloading tarball for FFTW3@v3.3.9: done   
==> Unpacking FFTW3@v3.3.9: done
==> Downloading tarball for ms_gsl@4.0.0: done  
==> Unpacking ms_gsl@4.0.0: done
==> Downloading tarball for pythia6@428-alice2: done    
==> Unpacking pythia6@428-alice2: done
==> Downloading tarball for protobuf@v21.9: done      
==> Unpacking protobuf@v21.9: done
==> Downloading tarball for hdf5@1.10.9: done      
==> Unpacking hdf5@1.10.9: done
==> Downloading tarball for curl@7.70.0: done   
==> Unpacking curl@7.70.0: done
==> Downloading tarball for FairCMakeModules@v1.0.0: done  
==> Unpacking FairCMakeModules@v1.0.0: done
==> Downloading tarball for libuv@v1.40.0: done   
==> Unpacking libuv@v1.40.0: done
==> Downloading tarball for lz4@v1.9.3: done   
==> Unpacking lz4@v1.9.3: done
==> Downloading tarball for GLFW@3.3.2: done   
==> Unpacking GLFW@3.3.2: done
==> Downloading tarball for re2@2019-09-01: done     
==> Unpacking re2@2019-09-01: done
==> Downloading tarball for HepMC@HEPMC_02_06_10: done      
==> Unpacking HepMC@HEPMC_02_06_10: done
==> Downloading tarball for ninja@fortran-v1.11.1.g9: done     
==> Unpacking ninja@fortran-v1.11.1.g9: done
==> Downloading tarball for libpng@v1.6.34: done    
==> Unpacking libpng@v1.6.34: done
==> Downloading tarball for double-conversion@v3.1.5: done   
==> Unpacking double-conversion@v3.1.5: done
==> Downloading tarball for TBB@v2021.5.0: done    
==> Unpacking TBB@v2021.5.0: done
==> Downloading tarball for abseil@20220623.1: done      
==> Unpacking abseil@20220623.1: done
==> Downloading tarball for libjalienO2@0.1.4: done   
==> Unpacking libjalienO2@0.1.4: done
==> Downloading tarball for sqlite@v3.15.0: done    
==> Unpacking sqlite@v3.15.0: done
==> Downloading tarball for googlebenchmark@1.6.1: done     
==> Unpacking googlebenchmark@1.6.1: done
==> Downloading tarball for xercesc@Xerces-C_3_2_5: done      
==> Unpacking xercesc@Xerces-C_3_2_5: done
==> Downloading tarball for fmt@10.1.1: done   
==> Unpacking fmt@10.1.1: done
==> Downloading tarball for Vc@1.4.1: done   
==> Unpacking Vc@1.4.1: done
==> Downloading tarball for libwebsockets@v4.3.2: done   
==> Unpacking libwebsockets@v4.3.2: done
==> Downloading tarball for flatbuffers@v24.3.25: done      
==> Unpacking flatbuffers@v24.3.25: done
==> Downloading tarball for ZeroMQ@v4.3.5: done      
==> Unpacking ZeroMQ@v4.3.5: done
==> Downloading tarball for Clang@v18.1.8: done      
==> Unpacking Clang@v18.1.8: done
==> Downloading tarball for DebugGUI@v0.8.0: done      
==> Unpacking DebugGUI@v0.8.0: done
==> Downloading tarball for RapidJSON@v1.1.0-alice2: done   
==> Unpacking RapidJSON@v1.1.0-alice2: done
==> Downloading tarball for grpc@v1.50.1: done      
==> Unpacking grpc@v1.50.1: done
==> Downloading tarball for Python@v3.9.16: done      
==> Unpacking Python@v3.9.16: done
==> Downloading tarball for GEANT4@v11.2.0: done      
==> Unpacking GEANT4@v11.2.0: done
==> Downloading tarball for FairLogger@v1.11.1: done   
==> Unpacking FairLogger@v1.11.1: done
==> Downloading tarball for VecGeom@v1.2.6: done      
==> Unpacking VecGeom@v1.2.6: done
==> Downloading tarball for xsimd@8.1.0: done   
==> Unpacking xsimd@8.1.0: done
==> Downloading tarball for bookkeeping-api@v0.93.0: done      
==> Unpacking bookkeeping-api@v0.93.0: done
==> Downloading tarball for Python-modules@1.0: done      
==> Unpacking Python-modules@1.0: done
==> Downloading tarball for XRootD@v5.7.0: done      
==> Unpacking XRootD@v5.7.0: done
==> Downloading tarball for boost@v1.83.0-alice2: done      
==> Unpacking boost@v1.83.0-alice2: done
==> Downloading tarball for xjalienfs@1.6.3: done      
==> Unpacking xjalienfs@1.6.3: done
==> Downloading tarball for arrow@v17.0.0-alice6: done      
==> Unpacking arrow@v17.0.0-alice6: done
==> Downloading tarball for Ppconsul@v0.2.3: done    
==> Unpacking Ppconsul@v0.2.3: done
==> Downloading tarball for pythia@v8311: done      
==> Unpacking pythia@v8311: done
==> Downloading tarball for Common-O2@v1.6.3: done    
==> Unpacking Common-O2@v1.6.3: done
==> Downloading tarball for FairMQ@v1.8.4: done      
==> Unpacking FairMQ@v1.8.4: done
==> Downloading tarball for cgal@4.12.2: done      
==> Unpacking cgal@4.12.2: done
==> Downloading tarball for libInfoLogger@v2.7.3: done     
==> Unpacking libInfoLogger@v2.7.3: done
==> Downloading tarball for ONNXRuntime@v1.18.1: done     
==> Unpacking ONNXRuntime@v1.18.1: done
==> Downloading tarball for Configuration@v2.8.0: done    
==> Unpacking Configuration@v2.8.0: done
==> Downloading tarball for ROOT@v6-32-06-alice1: done      
==> Unpacking ROOT@v6-32-06-alice1: done
==> Downloading tarball for generators@v1.0: done  
==> Unpacking generators@v1.0: done
==> Downloading tarball for fastjet@v3.4.1_1.052-alice2: done      
==> Unpacking fastjet@v3.4.1_1.052-alice2: done
==> Downloading tarball for Monitoring@v3.18.1: done     
==> Unpacking Monitoring@v3.18.1: done
==> Downloading tarball for HepMC3@3.3.0: done      
==> Unpacking HepMC3@3.3.0: done
==> Downloading tarball for vgm@v5-3: done      
==> Unpacking vgm@v5-3: done
==> Downloading tarball for KFParticle@v1.1-5: done      
==> Unpacking KFParticle@v1.1-5: done
==> Downloading tarball for JAliEn-ROOT@0.7.14: done      
==> Unpacking JAliEn-ROOT@0.7.14: done
==> Downloading tarball for VMC@v2-0: done   
==> Unpacking VMC@v2-0: done
==> Downloading tarball for MCStepLogger@v0.6.1: done     
==> Unpacking MCStepLogger@v0.6.1: done
==> Downloading tarball for GEANT3@v4-4: done      
==> Unpacking GEANT3@v4-4: done
==> Downloading tarball for GEANT4_VMC@v6-6-p1: done      
==> Unpacking GEANT4_VMC@v6-6-p1: done
==> Downloading tarball for simulation@v1.0: done  
==> Unpacking simulation@v1.0: done
==> Downloading tarball for FairRoot@v18.4.9-alice3: done      
==> Unpacking FairRoot@v18.4.9-alice3: done

  ...

```

## CRASHED WHEN COMPILING O2Physics use -j 2:

```
  rigel@rigel-Latitude-E6520:~/alice$ aliBuild build O2Physics -j 2

==> Packages will be built in the following order:
     - O2-customization@v1.0.0
     - Alice-GRID-Utils@0.0.7
     - GCC-Toolchain@v13.2.0-alice1
     - alibuild-recipe-tools@v0.2.5
     - lzma@v5.2.3
     - zlib@v1.2.8
     - GMP@v6.2.1
     - libtirpc@libtirpc-1-1-4
     - libffi@v3.2.1
     - bz2@8ca1faa31f396d94ab927b257f3a05236c84e330
     - lhapdf@v6.5.2
     - UUID@alice/v2.27.1
     - MLModels@20220530
     - Python-modules-list@1.0
     - AliEn-CAs@f62625ede780d455b3b7878064bcfee6bd9a4f53
     - ITSResponse@v1.0.0
     - GSL@release-1-16
     - libxml2@v2.9.3
     - FreeType@VER-2-10-1
     - OpenSSL@OpenSSL_1_1_1m
     - MPFR@v3.1.3
     - ApMon-CPP@v2.2.8-alice6
     - CMake@v3.28.1
     - AliEn-Runtime@v2-19-le
     - ninja@v1.11.1.g95dee.kitware.jobserver-1
     - FFTW3@v3.3.9
     - ms_gsl@v4.0.0
     - protobuf@v21.9
     - curl@curl-7_70_0
     - utf8proc@v2.6.1
     - libuv@v1.40.0
     - c-ares@cares-1_18_1
     - hdf5@hdf5-1_10_9
     - FairCMakeModules@v1.0.0
     - GLFW@3.3.2
     - libpng@v1.6.34
     - abseil@20220623.1
     - pythia6@428-alice2
     - lz4@v1.9.3
     - json-c@json-c-0.17-20230812
     - double-conversion@v3.1.5
     - TBB@v2021.5.0
     - re2@2019-09-01
     - HepMC@HEPMC_02_06_10
     - libjalienO2@0.1.4
     - flatbuffers@v24.3.25
     - RapidJSON@091de040edb3355dcf2f4a18c425aec51b906f08
     - Vc@1.4.1
     - fmt@10.1.1
     - xercesc@v3.2.5
     - ZeroMQ@v4.3.5
     - googlebenchmark@v1.6.1
     - Clang@llvmorg-18.1.8-alice2
     - sqlite@v3.15.0
     - libwebsockets@v4.3.2
     - DebugGUI@v0.8.0
     - grpc@v1.50.1
     - VecGeom@v1.2.6
     - FairLogger@v1.11.1
     - GEANT4@v11.2.0
     - xsimd@8.1.0
     - Python@v3.9.16
     - bookkeeping-api@@aliceo2/bookkeeping@0.93.0
     - Python-modules@1.0
     - boost@v1.83.0-alice2
     - XRootD@v5.7.0
     - Common-O2@v1.6.3
     - ONNXRuntime@v1.18.1
     - FairMQ@v1.8.4
     - arrow@apache-arrow-17.0.0-alice6
     - libInfoLogger@v2.7.3
     - cgal@4.12.2
     - Ppconsul@v0.2.3
     - pythia@v8311
     - xjalienfs@1.6.3
     - Monitoring@v3.18.1
     - fastjet@v3.4.1_1.052-alice2
     - Configuration@v2.8.0
     - generators@vAN-20210812
     - ROOT@v6-32-06-alice1
     - HepMC3@3.3.0
     - VMC@v2-0
     - KFParticle@alice/v1.1-5
     - vgm@v5-3
     - JAliEn-ROOT@0.7.14
     - MCStepLogger@v0.6.1
     - GEANT3@v4-4
     - GEANT4_VMC@v6-6-p1
     - simulation@v1.0
     - FairRoot@v18.4.9-alice3
     - O2@daily-20241015-0200
     - O2Physics (development package)

==> You have packages in development mode (O2Physics).
    This means their source code can be freely modified under:
    
      /home/rigel/alice/<package_name>
    
    aliBuild does not automatically update such packages to avoid work loss.
    In most cases this is achieved by doing in the package source directory:
    
      git pull --rebase
    
==> Updating repositories: done  
==> Compiling O2Physics@master (use --debug for full output): done      
2024-10-16@09:30:51:ERROR:O2Physics:O2Physics:0: GET https://s3.cern.ch/swift/v1/alibuild-repo/TARS/ubuntu2204_x86-64/O2Physics.manifest failed: HTTPSConnectionPool(host='s3.cern.ch', port=443): Max retries exceeded with url: /swift/v1/alibuild-repo/TARS/ubuntu2204_x86-64/O2Physics.manifest (Caused by NewConnectionError('<urllib3.connection.HTTPSConnection object at 0x7fac1fa7f010>: Failed to establish a new connection: [Errno -3] Temporary failure in name resolution'))
Traceback (most recent call last):
  File "/usr/bin/aliBuild", line 133, in <module>
    doMain(args, parser)
  File "/usr/bin/aliBuild", line 83, in doMain
    doBuild(args, parser)
  File "/usr/lib/python3/dist-packages/alibuild_helpers/build.py", line 740, in doBuild
    syncHelper.fetch_symlinks(spec)
  File "/usr/lib/python3/dist-packages/alibuild_helpers/sync.py", line 208, in fetch_symlinks
    for line in manifest.splitlines())
AttributeError: 'NoneType' object has no attribute 'splitlines'
rigel@rigel-Latitude-E6520:~/alice$ aliBuild build O2Physics

==> Packages will be built in the following order:
     - alibuild-recipe-tools@v0.2.5
     - O2-customization@v1.0.0
     - GCC-Toolchain@v13.2.0-alice1
     - Alice-GRID-Utils@0.0.7
     - AliEn-CAs@f62625ede780d455b3b7878064bcfee6bd9a4f53
     - ITSResponse@v1.0.0
     - MLModels@20220530
     - Python-modules-list@1.0
     - libffi@v3.2.1
     - bz2@8ca1faa31f396d94ab927b257f3a05236c84e330
     - GMP@v6.2.1
     - lhapdf@v6.5.2
     - lzma@v5.2.3
     - UUID@alice/v2.27.1
     - libtirpc@libtirpc-1-1-4
     - GSL@release-1-16
     - zlib@v1.2.8
     - MPFR@v3.1.3
     - ApMon-CPP@v2.2.8-alice6
     - OpenSSL@OpenSSL_1_1_1m
     - FreeType@VER-2-10-1
     - libxml2@v2.9.3
     - CMake@v3.28.1
     - AliEn-Runtime@v2-19-le
     - HepMC@HEPMC_02_06_10
     - abseil@20220623.1
     - FairCMakeModules@v1.0.0
     - curl@curl-7_70_0
     - json-c@json-c-0.17-20230812
     - utf8proc@v2.6.1
     - lz4@v1.9.3
     - ms_gsl@v4.0.0
     - FFTW3@v3.3.9
     - GLFW@3.3.2
     - protobuf@v21.9
     - libuv@v1.40.0
     - libpng@v1.6.34
     - TBB@v2021.5.0
     - double-conversion@v3.1.5
     - re2@2019-09-01
     - pythia6@428-alice2
     - ninja@v1.11.1.g95dee.kitware.jobserver-1
     - hdf5@hdf5-1_10_9
     - c-ares@cares-1_18_1
     - libjalienO2@0.1.4
     - sqlite@v3.15.0
     - flatbuffers@v24.3.25
     - xercesc@v3.2.5
     - libwebsockets@v4.3.2
     - Clang@llvmorg-18.1.8-alice2
     - Vc@1.4.1
     - DebugGUI@v0.8.0
     - fmt@10.1.1
     - RapidJSON@091de040edb3355dcf2f4a18c425aec51b906f08
     - ZeroMQ@v4.3.5
     - googlebenchmark@v1.6.1
     - grpc@v1.50.1
     - Python@v3.9.16
     - GEANT4@v11.2.0
     - xsimd@8.1.0
     - VecGeom@v1.2.6
     - FairLogger@v1.11.1
     - bookkeeping-api@@aliceo2/bookkeeping@0.93.0
     - Python-modules@1.0
     - boost@v1.83.0-alice2
     - XRootD@v5.7.0
     - Common-O2@v1.6.3
     - arrow@apache-arrow-17.0.0-alice6
     - libInfoLogger@v2.7.3
     - pythia@v8311
     - ONNXRuntime@v1.18.1
     - cgal@4.12.2
     - FairMQ@v1.8.4
     - Ppconsul@v0.2.3
     - xjalienfs@1.6.3
     - Monitoring@v3.18.1
     - ROOT@v6-32-06-alice1
     - generators@vAN-20210812
     - fastjet@v3.4.1_1.052-alice2
     - Configuration@v2.8.0
     - KFParticle@alice/v1.1-5
     - JAliEn-ROOT@0.7.14
     - VMC@v2-0
     - vgm@v5-3
     - HepMC3@3.3.0
     - GEANT3@v4-4
     - MCStepLogger@v0.6.1
     - GEANT4_VMC@v6-6-p1
     - simulation@v1.0
     - FairRoot@v18.4.9-alice3
     - O2@daily-20241015-0200
     - O2Physics (development package)

==> You have packages in development mode (O2Physics).
    This means their source code can be freely modified under:
    
      /home/rigel/alice/<package_name>
    
    aliBuild does not automatically update such packages to avoid work loss.
    In most cases this is achieved by doing in the package source directory:
    
      git pull --rebase
    
==> Updating repositories: done   
Development package O2Physics does not need rebuild

==> Build of O2Physics successfully completed on `rigel-Latitude-E6520'.
    Your software installation is at:
    
      /home/rigel/alice/sw/ubuntu2204_x86-64
    
    You can use this package by loading the environment:
    
      alienv enter O2Physics/latest-master-o2

==> Build directory for devel package O2Physics:
    /home/rigel/alice/sw/BUILD/O2Physics-latest/O2Physics
```

# Start alienv and run example

```
rigel@rigel-Latitude-E6520:~/alice$ alienv enter O2Physics
ERROR: O2Physics was not found
rigel@rigel-Latitude-E6520:~/alice$ alienv enter O2Physics/latest
Loading O2Physics/latest
  Loading requirement: BASE/1.0 libffi/v3.2.1-9 lz4/v1.9.3-13
    GCC-Toolchain/v13.2.0-alice1-3 zlib/v1.2.8-8 FreeType/v2.10.1-13
    hdf5/1.10.9-4 AliEn-Runtime/v2-19-le-15 sqlite/v3.15.0-16 libpng/v1.6.34-13
    Python/v3.9.16-21 Python-modules/1.0-37 boost/v1.83.0-alice2-18
    OpenSSL/v1.1.1m-11 protobuf/v21.9-14 Clang/v18.1.8-4 utf8proc/v2.6.1-13
    xsimd/8.1.0-22 arrow/v17.0.0-alice6-11 lhapdf/v6.5.2-7
    HepMC/HEPMC_02_06_10-13 pythia/v8311-16 pythia6/428-alice2-13
    generators/v1.0-40 fmt/10.1.1-13 FairLogger/v1.11.1-17 libuv/v1.40.0-15
    GLFW/3.3.2-13 DebugGUI/v0.8.0-17 ms_gsl/4.0.0-13 curl/7.70.0-15
    libInfoLogger/v2.7.3-1 GSL/v1.16-9 libxml2/v2.9.3-8 XRootD/v5.7.0-12
    xjalienfs/1.6.3-4 Ppconsul/v0.2.3-39 xercesc/Xerces-C_3_2_5-7
    GEANT4/v11.2.0-11 Vc/1.4.1-14 TBB/v2021.5.0-14 FFTW3/v3.3.9-14 lzma/v5.2.3-8
    ROOT/v6-32-06-alice1-4 VMC/v2-0-66 vgm/v5-3-23 GEANT4_VMC/v6-6-p1-31
    GEANT3/v4-4-5 simulation/v1.0-73 ZeroMQ/v4.3.5-12 FairMQ/v1.8.4-29
    c-ares/1.18.1-14 re2/2019-09-01-13 grpc/v1.50.1-19
    FairRoot/v18.4.9-alice3-51 HepMC3/3.3.0-21 Monitoring/v3.18.1-32
    Configuration/v2.8.0-20 Common-O2/v1.6.3-1 libwebsockets/v4.3.2-15
    JAliEn-ROOT/0.7.14-16 cgal/4.12.2-40 GMP/v6.2.1-9
    fastjet/v3.4.1_1.052-alice2-31 libjalienO2/0.1.4-18 abseil/20220623.1-14
    ONNXRuntime/v1.18.1-3 RapidJSON/v1.1.0-alice2-15 MLModels/20220530-5
    bookkeeping-api/v0.93.0-5 O2/daily-20241015-0200-local1 KFParticle/v1.1-5-66
    MCStepLogger/v0.6.1-21 VecGeom/v1.2.6-12
Currently Loaded Modulefiles:
 1) BASE/1.0                        39) GEANT4/v11.2.0-11               
 2) libffi/v3.2.1-9                 40) Vc/1.4.1-14                     
 3) lz4/v1.9.3-13                   41) TBB/v2021.5.0-14                
 4) GCC-Toolchain/v13.2.0-alice1-3  42) FFTW3/v3.3.9-14                 
 5) zlib/v1.2.8-8                   43) lzma/v5.2.3-8                   
 6) FreeType/v2.10.1-13             44) ROOT/v6-32-06-alice1-4          
 7) hdf5/1.10.9-4                   45) VMC/v2-0-66                     
 8) AliEn-Runtime/v2-19-le-15       46) vgm/v5-3-23                     
 9) sqlite/v3.15.0-16               47) GEANT4_VMC/v6-6-p1-31           
10) libpng/v1.6.34-13               48) GEANT3/v4-4-5                   
11) Python/v3.9.16-21               49) simulation/v1.0-73              
12) Python-modules/1.0-37           50) ZeroMQ/v4.3.5-12                
13) boost/v1.83.0-alice2-18         51) FairMQ/v1.8.4-29                
14) OpenSSL/v1.1.1m-11              52) c-ares/1.18.1-14                
15) protobuf/v21.9-14               53) re2/2019-09-01-13               
16) Clang/v18.1.8-4                 54) grpc/v1.50.1-19                 
17) utf8proc/v2.6.1-13              55) FairRoot/v18.4.9-alice3-51      
18) xsimd/8.1.0-22                  56) HepMC3/3.3.0-21                 
19) arrow/v17.0.0-alice6-11         57) Monitoring/v3.18.1-32           
20) lhapdf/v6.5.2-7                 58) Configuration/v2.8.0-20         
21) HepMC/HEPMC_02_06_10-13         59) Common-O2/v1.6.3-1              
22) pythia/v8311-16                 60) libwebsockets/v4.3.2-15         
23) pythia6/428-alice2-13           61) JAliEn-ROOT/0.7.14-16           
Use alienv list to list loaded modules. Use exit to exit this environment.
[O2Physics/latest] ~/alice $> ls
alidist  O2Physics  sw
[O2Physics/latest] ~/alice $> cd O2Physics/
[O2Physics/latest] ~/alice/O2Physics $> ls
ALICE3		compile_commands.json  EventFiltering  PWGHF  pyproject.toml
cmake		COPYING		       packaging       PWGJE  README.md
CMakeLists.txt	CPPLINT.cfg	       PWGCF	       PWGLF  Scripts
CODEOWNERS	dependencies	       PWGDQ	       PWGMM  Tools
Common		DPG		       PWGEM	       PWGUD  Tutorials
[O2Physics/latest] ~/alice/O2Physics $> cd Tutorials/PWGMM
[O2Physics/latest] ~/alice/O2Physics/Tutorials/PWGMM $> ls
CMakeLists.txt	myExampleTask.cxx  README.md
[O2Physics/latest] ~/alice/O2Physics/Tutorials/PWGMM $> ls
CMakeLists.txt	myExampleTask.cxx  README.md
[O2Physics/latest] ~/alice/O2Physics/Tutorials/PWGMM $> cp ~/Documents/AO2D.root .
[O2Physics/latest] ~/alice/O2Physics/Tutorials/PWGMM $> ll
bash: ll: command not found
[O2Physics/latest] ~/alice/O2Physics/Tutorials/PWGMM $> ls
AO2D.root  CMakeLists.txt  myExampleTask.cxx  README.md
[O2Physics/latest] ~/alice/O2Physics/Tutorials/PWGMM $> ll
bash: ll: command not found
[O2Physics/latest] ~/alice/O2Physics/Tutorials/PWGMM $> ls
AO2D.root  CMakeLists.txt  myExampleTask.cxx  README.md
[O2Physics/latest] ~/alice/O2Physics/Tutorials/PWGMM $> o2-analysistutorial-mm-my-example-task --aod-file AO2D.root 
[INFO] Loading metadata from file AO2D.root in PID 107157
[INFO] Metadata for file "AO2D.root":
[INFO] - O2Version: 1.2.0
[INFO] - LPMProductionTag: LHC23zzh
[INFO] - ROOTVersion: 6.30/01
[INFO] - RecoPassName: apass4
[INFO] - Run: 3
[INFO] - AnchorPassName: 
[INFO] - DataType: RAW
[INFO] - AnchorProduction: 
[INFO] Initialising O2 Data Processing Layer. Driver PID: 107157.
[INFO] Driver listening on port: 25237
[INFO] Rate limiting set up at 500MB distributed over 1 readers
[INFO] O2 Data Processing Layer initialised. We brake for nobody.
[INFO] Optimised build. O2DEBUG / LOG(debug) / LOGF(debug) / assert statement will not be shown.
[INFO] Redeployment of configuration asked.
[INFO] Starting internal-dpl-clock on pid 107170
[INFO] Starting internal-dpl-aod-reader on pid 107171
[INFO] Starting internal-dpl-aod-spawner on pid 107172
[INFO] Starting my-example-task on pid 107173
[INFO] Starting internal-dpl-aod-global-analysis-file-sink on pid 107174
[INFO] Starting internal-dpl-injected-dummy-sink on pid 107175
[INFO] Redeployment of configuration done.
[107170:internal-dpl-clock]: [INFO] Instrumenting crash signals
[107170:internal-dpl-clock]: [INFO] Spawing new device internal-dpl-clock in process with pid 107170
[107170:internal-dpl-clock]: [09:46:39][INFO] 
[107170:internal-dpl-clock]:       ______      _    _______  _________ 
[107170:internal-dpl-clock]:      / ____/___ _(_)_______   |/  /_  __ \    version 1.8.4
[107170:internal-dpl-clock]:     / /_  / __ `/ / ___/__  /|_/ /_  / / /    build RELWITHDEBINFO
[107170:internal-dpl-clock]:    / __/ / /_/ / / /    _  /  / / / /_/ /     https://github.com/FairRootGroup/FairMQ
[107170:internal-dpl-clock]:   /_/    \__,_/_/_/     /_/  /_/  \___\_\     LGPL-3.0  © 2012-2023 GSI
[107170:internal-dpl-clock]: 
[107170:internal-dpl-clock]: [09:46:39][STATE] Starting FairMQ state machine --> IDLE
[107170:internal-dpl-clock]: [09:46:39][STATE] IDLE ---> INITIALIZING DEVICE
[107170:internal-dpl-clock]: [09:46:39][STATE] INITIALIZING DEVICE ---> INITIALIZED
[107170:internal-dpl-clock]: [09:46:39][STATE] INITIALIZED ---> BINDING
[107170:internal-dpl-clock]: [09:46:39][STATE] BINDING ---> BOUND
[107170:internal-dpl-clock]: [09:46:39][STATE] BOUND ---> CONNECTING
[107170:internal-dpl-clock]: [09:46:39][STATE] CONNECTING ---> DEVICE READY
[107170:internal-dpl-clock]: [09:46:39][STATE] DEVICE READY ---> INITIALIZING TASK
[107170:internal-dpl-clock]: [09:46:39][STATE] INITIALIZING TASK ---> READY
[107170:internal-dpl-clock]: [09:46:39][STATE] READY ---> RUNNING
[107170:internal-dpl-clock]: [09:46:39][INFO] fair::mq::Device running...
[107170:internal-dpl-clock]: [09:46:39][INFO] LHCPeriod is not available, using current month OCT
[107171:internal-dpl-aod-reader]: [INFO] Instrumenting crash signals
[107171:internal-dpl-aod-reader]: [INFO] Spawing new device internal-dpl-aod-reader in process with pid 107171
[107171:internal-dpl-aod-reader]: [09:46:39][INFO] 
[107171:internal-dpl-aod-reader]:       ______      _    _______  _________ 
[107171:internal-dpl-aod-reader]:      / ____/___ _(_)_______   |/  /_  __ \    version 1.8.4
[107171:internal-dpl-aod-reader]:     / /_  / __ `/ / ___/__  /|_/ /_  / / /    build RELWITHDEBINFO
[107171:internal-dpl-aod-reader]:    / __/ / /_/ / / /    _  /  / / / /_/ /     https://github.com/FairRootGroup/FairMQ
[107171:internal-dpl-aod-reader]:   /_/    \__,_/_/_/     /_/  /_/  \___\_\     LGPL-3.0  © 2012-2023 GSI
[107171:internal-dpl-aod-reader]: 
[107171:internal-dpl-aod-reader]: [09:46:39][STATE] Starting FairMQ state machine --> IDLE
[107171:internal-dpl-aod-reader]: [09:46:39][STATE] IDLE ---> INITIALIZING DEVICE
[107171:internal-dpl-aod-reader]: [09:46:39][STATE] INITIALIZING DEVICE ---> INITIALIZED
[107171:internal-dpl-aod-reader]: [09:46:39][STATE] INITIALIZED ---> BINDING
[107171:internal-dpl-aod-reader]: [09:46:39][STATE] BINDING ---> BOUND
[107171:internal-dpl-aod-reader]: [09:46:39][STATE] BOUND ---> CONNECTING
[107171:internal-dpl-aod-reader]: [09:46:39][STATE] CONNECTING ---> DEVICE READY
[107171:internal-dpl-aod-reader]: [09:46:39][STATE] DEVICE READY ---> INITIALIZING TASK
[107171:internal-dpl-aod-reader]: [09:46:39][STATE] INITIALIZING TASK ---> READY
[107171:internal-dpl-aod-reader]: [09:46:39][STATE] READY ---> RUNNING
[107171:internal-dpl-aod-reader]: [09:46:39][INFO] fair::mq::Device running...
[107171:internal-dpl-aod-reader]: [09:46:39][INFO] LHCPeriod is not available, using current month OCT
[107172:internal-dpl-aod-spawner]: [INFO] Instrumenting crash signals
[107172:internal-dpl-aod-spawner]: [INFO] Spawing new device internal-dpl-aod-spawner in process with pid 107172
[107172:internal-dpl-aod-spawner]: [09:46:39][INFO] 
[107172:internal-dpl-aod-spawner]:       ______      _    _______  _________ 
[107172:internal-dpl-aod-spawner]:      / ____/___ _(_)_______   |/  /_  __ \    version 1.8.4
[107172:internal-dpl-aod-spawner]:     / /_  / __ `/ / ___/__  /|_/ /_  / / /    build RELWITHDEBINFO
[107172:internal-dpl-aod-spawner]:    / __/ / /_/ / / /    _  /  / / / /_/ /     https://github.com/FairRootGroup/FairMQ
[107172:internal-dpl-aod-spawner]:   /_/    \__,_/_/_/     /_/  /_/  \___\_\     LGPL-3.0  © 2012-2023 GSI
[107172:internal-dpl-aod-spawner]: 
[107172:internal-dpl-aod-spawner]: [09:46:39][STATE] Starting FairMQ state machine --> IDLE
[107172:internal-dpl-aod-spawner]: [09:46:39][STATE] IDLE ---> INITIALIZING DEVICE
[107172:internal-dpl-aod-spawner]: [09:46:39][STATE] INITIALIZING DEVICE ---> INITIALIZED
[107172:internal-dpl-aod-spawner]: [09:46:39][STATE] INITIALIZED ---> BINDING
[107172:internal-dpl-aod-spawner]: [09:46:39][STATE] BINDING ---> BOUND
[107172:internal-dpl-aod-spawner]: [09:46:39][STATE] BOUND ---> CONNECTING
[107172:internal-dpl-aod-spawner]: [09:46:39][STATE] CONNECTING ---> DEVICE READY
[107172:internal-dpl-aod-spawner]: [09:46:39][STATE] DEVICE READY ---> INITIALIZING TASK
[107172:internal-dpl-aod-spawner]: [09:46:39][STATE] INITIALIZING TASK ---> READY
[107172:internal-dpl-aod-spawner]: [09:46:39][STATE] READY ---> RUNNING
[107172:internal-dpl-aod-spawner]: [09:46:39][INFO] fair::mq::Device running...
[107172:internal-dpl-aod-spawner]: [09:46:39][INFO] LHCPeriod is not available, using current month OCT
[107173:my-example-task]: [INFO] Instrumenting crash signals
[107173:my-example-task]: [INFO] Spawing new device my-example-task in process with pid 107173
[107173:my-example-task]: [09:46:39][INFO] 
[107173:my-example-task]:       ______      _    _______  _________ 
[107173:my-example-task]:      / ____/___ _(_)_______   |/  /_  __ \    version 1.8.4
[107173:my-example-task]:     / /_  / __ `/ / ___/__  /|_/ /_  / / /    build RELWITHDEBINFO
[107173:my-example-task]:    / __/ / /_/ / / /    _  /  / / / /_/ /     https://github.com/FairRootGroup/FairMQ
[107173:my-example-task]:   /_/    \__,_/_/_/     /_/  /_/  \___\_\     LGPL-3.0  © 2012-2023 GSI
[107173:my-example-task]: 
[107173:my-example-task]: [09:46:39][STATE] Starting FairMQ state machine --> IDLE
[107173:my-example-task]: [09:46:39][STATE] IDLE ---> INITIALIZING DEVICE
[107173:my-example-task]: [09:46:39][STATE] INITIALIZING DEVICE ---> INITIALIZED
[107173:my-example-task]: [09:46:39][STATE] INITIALIZED ---> BINDING
[107173:my-example-task]: [09:46:39][STATE] BINDING ---> BOUND
[107173:my-example-task]: [09:46:39][STATE] BOUND ---> CONNECTING
[107173:my-example-task]: [09:46:39][STATE] CONNECTING ---> DEVICE READY
[107173:my-example-task]: [09:46:39][STATE] DEVICE READY ---> INITIALIZING TASK
[107173:my-example-task]: [09:46:39][STATE] INITIALIZING TASK ---> READY
[107173:my-example-task]: [09:46:39][STATE] READY ---> RUNNING
[107173:my-example-task]: [09:46:39][INFO] fair::mq::Device running...
[107173:my-example-task]: [09:46:39][INFO] LHCPeriod is not available, using current month OCT
[107174:internal-dpl-aod-global-analysis-file-sink]: [INFO] Instrumenting crash signals
[107174:internal-dpl-aod-global-analysis-file-sink]: [INFO] Spawing new device internal-dpl-aod-global-analysis-file-sink in process with pid 107174
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:39][INFO] 
[107174:internal-dpl-aod-global-analysis-file-sink]:       ______      _    _______  _________ 
[107174:internal-dpl-aod-global-analysis-file-sink]:      / ____/___ _(_)_______   |/  /_  __ \    version 1.8.4
[107174:internal-dpl-aod-global-analysis-file-sink]:     / /_  / __ `/ / ___/__  /|_/ /_  / / /    build RELWITHDEBINFO
[107174:internal-dpl-aod-global-analysis-file-sink]:    / __/ / /_/ / / /    _  /  / / / /_/ /     https://github.com/FairRootGroup/FairMQ
[107174:internal-dpl-aod-global-analysis-file-sink]:   /_/    \__,_/_/_/     /_/  /_/  \___\_\     LGPL-3.0  © 2012-2023 GSI
[107174:internal-dpl-aod-global-analysis-file-sink]: 
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:39][STATE] Starting FairMQ state machine --> IDLE
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:39][STATE] IDLE ---> INITIALIZING DEVICE
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:39][STATE] INITIALIZING DEVICE ---> INITIALIZED
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:39][STATE] INITIALIZED ---> BINDING
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:39][STATE] BINDING ---> BOUND
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:39][STATE] BOUND ---> CONNECTING
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:39][STATE] CONNECTING ---> DEVICE READY
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:39][STATE] DEVICE READY ---> INITIALIZING TASK
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:39][STATE] INITIALIZING TASK ---> READY
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:39][STATE] READY ---> RUNNING
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:39][INFO] fair::mq::Device running...
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:39][INFO] LHCPeriod is not available, using current month OCT
[107175:internal-dpl-injected-dummy-sink]: [INFO] Instrumenting crash signals
[107175:internal-dpl-injected-dummy-sink]: [INFO] Spawing new device internal-dpl-injected-dummy-sink in process with pid 107175
[107175:internal-dpl-injected-dummy-sink]: [09:46:39][INFO] 
[107175:internal-dpl-injected-dummy-sink]:       ______      _    _______  _________ 
[107175:internal-dpl-injected-dummy-sink]:      / ____/___ _(_)_______   |/  /_  __ \    version 1.8.4
[107175:internal-dpl-injected-dummy-sink]:     / /_  / __ `/ / ___/__  /|_/ /_  / / /    build RELWITHDEBINFO
[107175:internal-dpl-injected-dummy-sink]:    / __/ / /_/ / / /    _  /  / / / /_/ /     https://github.com/FairRootGroup/FairMQ
[107175:internal-dpl-injected-dummy-sink]:   /_/    \__,_/_/_/     /_/  /_/  \___\_\     LGPL-3.0  © 2012-2023 GSI
[107175:internal-dpl-injected-dummy-sink]: 
[107175:internal-dpl-injected-dummy-sink]: [09:46:39][STATE] Starting FairMQ state machine --> IDLE
[107175:internal-dpl-injected-dummy-sink]: [09:46:39][STATE] IDLE ---> INITIALIZING DEVICE
[107175:internal-dpl-injected-dummy-sink]: [09:46:39][STATE] INITIALIZING DEVICE ---> INITIALIZED
[107175:internal-dpl-injected-dummy-sink]: [09:46:39][STATE] INITIALIZED ---> BINDING
[107175:internal-dpl-injected-dummy-sink]: [09:46:39][STATE] BINDING ---> BOUND
[107175:internal-dpl-injected-dummy-sink]: [09:46:39][STATE] BOUND ---> CONNECTING
[107175:internal-dpl-injected-dummy-sink]: [09:46:39][STATE] CONNECTING ---> DEVICE READY
[107175:internal-dpl-injected-dummy-sink]: [09:46:39][STATE] DEVICE READY ---> INITIALIZING TASK
[107175:internal-dpl-injected-dummy-sink]: [09:46:39][STATE] INITIALIZING TASK ---> READY
[107175:internal-dpl-injected-dummy-sink]: [09:46:39][STATE] READY ---> RUNNING
[107175:internal-dpl-injected-dummy-sink]: [09:46:39][INFO] fair::mq::Device running...
[107175:internal-dpl-injected-dummy-sink]: [09:46:39][INFO] LHCPeriod is not available, using current month OCT
[107170:internal-dpl-clock]: [09:46:39][INFO] Correctly handshaken websocket connection.
[107171:internal-dpl-aod-reader]: [09:46:39][INFO] Correctly handshaken websocket connection.
[107172:internal-dpl-aod-spawner]: [09:46:39][INFO] Correctly handshaken websocket connection.
[107173:my-example-task]: [09:46:39][INFO] Correctly handshaken websocket connection.
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:39][INFO] Correctly handshaken websocket connection.
[107175:internal-dpl-injected-dummy-sink]: [09:46:39][INFO] Correctly handshaken websocket connection.
[107172:internal-dpl-aod-spawner]: /local/workspace/DailyBuilds/DailyO2-ubuntu2204/daily-tags.5v3z73pGkk/BUILD/5ed8fd940e1ca14369b127add023931c8f2e2f38/arrow/src_tmp/cpp/src/gandiva/cache.cc:61: Creating gandiva cache with capacity of 5000
[107172:internal-dpl-aod-spawner]: /local/workspace/DailyBuilds/DailyO2-ubuntu2204/daily-tags.5v3z73pGkk/BUILD/5ed8fd940e1ca14369b127add023931c8f2e2f38/arrow/src_tmp/cpp/src/gandiva/engine.cc:276: Detected CPU Name : sandybridge
[107172:internal-dpl-aod-spawner]: /local/workspace/DailyBuilds/DailyO2-ubuntu2204/daily-tags.5v3z73pGkk/BUILD/5ed8fd940e1ca14369b127add023931c8f2e2f38/arrow/src_tmp/cpp/src/gandiva/engine.cc:277: Detected CPU Features: [ -prfchw -cldemote +avx +aes +sahf +pclmul -xop +crc32 -xsaves -avx512fp16 -usermsr -sm4 +sse4.1 -avx512ifma +xsave -avx512pf +sse4.2 -tsxldtrk -ptwrite -widekl -sm3 -invpcid +64bit -xsavec -avx10.1-512 -avx512vpopcntdq +cmov -avx512vp2intersect -avx512cd -movbe -avxvnniint8 -avx512er -amx-int8 -kl -avx10.1-256 -sha512 -avxvnni -rtm -adx -avx2 -hreset -movdiri -serialize -vpclmulqdq -avx512vl -uintr -clflushopt -raoint -cmpccxadd -bmi -amx-tile +sse -gfni -avxvnniint16 -amx-fp16 +xsaveopt -rdrnd -avx512f -amx-bf16 -avx512bf16 -avx512vnni +cx8 -avx512bw +sse3 -pku -fsgsbase -clzero -mwaitx -lwp -lzcnt -sha -movdir64b -wbnoinvd -enqcmd -prefetchwt1 -avxneconvert -tbm -pconfig -amx-complex +ssse3 +cx16 -bmi2 -fma +popcnt -avxifma -f16c -avx512bitalg -rdpru -clwb +mmx +sse2 -rdseed -avx512vbmi2 -prefetchi -rdpid -fma4 -avx512vbmi -shstk -vaes -waitpkg -sgx +fxsr -avx512dq -sse4a]
[107171:internal-dpl-aod-reader]: [09:46:51][INFO] No input files left to read for reader 0!
[107171:internal-dpl-aod-reader]: [09:46:51][INFO] Read info: lfn=AO2D.root,size=2077790626,total_df=36,read_df=36,read_bytes=661276104,read_calls=669,io_time=6.2,wait_time=5.3,level=0
[107171:internal-dpl-aod-reader]: [09:46:51][INFO] Sending end-of-stream message to channel from_internal-dpl-aod-reader_to_internal-dpl-aod-spawner
[107171:internal-dpl-aod-reader]: [09:46:51][INFO] Sending end-of-stream message to channel from_internal-dpl-aod-reader_to_internal-dpl-injected-dummy-sink
[107172:internal-dpl-aod-spawner]: [09:46:54][INFO] Sending end-of-stream message to channel from_internal-dpl-aod-spawner_to_my-example-task
[107173:my-example-task]: [09:46:55][INFO] Sending end-of-stream message to channel from_my-example-task_to_internal-dpl-aod-global-analysis-file-sink
[INFO] Quitting
[INFO] QUIT_REQUESTED
[107175:internal-dpl-injected-dummy-sink]: [09:46:56][INFO] Received device shutdown request (signal 15).
[107175:internal-dpl-injected-dummy-sink]: [09:46:56][INFO] Waiting for graceful device shutdown. Hit Ctrl-C again to abort immediately.
[107175:internal-dpl-injected-dummy-sink]: [09:46:56][INFO] New state requested. No timeout set, quitting immediately as per --completion-policy
[107175:internal-dpl-injected-dummy-sink]: [09:46:56][STATE] RUNNING ---> READY
[107175:internal-dpl-injected-dummy-sink]: [09:46:56][STATE] READY ---> RESETTING TASK
[107175:internal-dpl-injected-dummy-sink]: [09:46:56][STATE] RESETTING TASK ---> DEVICE READY
[107175:internal-dpl-injected-dummy-sink]: [09:46:56][STATE] DEVICE READY ---> RESETTING DEVICE
[107170:internal-dpl-clock]: [09:46:56][INFO] Received device shutdown request (signal 15).
[107170:internal-dpl-clock]: [09:46:56][INFO] Waiting for graceful device shutdown. Hit Ctrl-C again to abort immediately.
[107170:internal-dpl-clock]: [09:46:56][INFO] New state requested. No timeout set, quitting immediately as per --completion-policy
[107170:internal-dpl-clock]: [09:46:56][INFO] Sending end-of-stream message to channel from_internal-dpl-clock_to_internal-dpl-aod-reader
[107170:internal-dpl-clock]: [09:46:56][STATE] RUNNING ---> READY
[107175:internal-dpl-injected-dummy-sink]: [09:46:56][STATE] RESETTING DEVICE ---> IDLE
[107170:internal-dpl-clock]: [09:46:56][STATE] READY ---> RESETTING TASK
[107175:internal-dpl-injected-dummy-sink]: [09:46:56][STATE] IDLE ---> EXITING
[107170:internal-dpl-clock]: [09:46:56][STATE] RESETTING TASK ---> DEVICE READY
[107170:internal-dpl-clock]: [09:46:56][STATE] DEVICE READY ---> RESETTING DEVICE
[107175:internal-dpl-injected-dummy-sink]: [09:46:56][STATE] Exiting FairMQ state machine
[107170:internal-dpl-clock]: [09:46:56][STATE] RESETTING DEVICE ---> IDLE
[107170:internal-dpl-clock]: [09:46:56][STATE] IDLE ---> EXITING
[107170:internal-dpl-clock]: [09:46:56][STATE] Exiting FairMQ state machine
[107172:internal-dpl-aod-spawner]: [09:46:56][INFO] Received device shutdown request (signal 15).
[107172:internal-dpl-aod-spawner]: [09:46:56][INFO] Waiting for graceful device shutdown. Hit Ctrl-C again to abort immediately.
[107173:my-example-task]: [09:46:56][INFO] Received device shutdown request (signal 15).
[107173:my-example-task]: [09:46:56][INFO] Waiting for graceful device shutdown. Hit Ctrl-C again to abort immediately.
[107171:internal-dpl-aod-reader]: [09:46:56][INFO] Received device shutdown request (signal 15).
[107171:internal-dpl-aod-reader]: [09:46:56][INFO] Waiting for graceful device shutdown. Hit Ctrl-C again to abort immediately.
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:56][INFO] Received device shutdown request (signal 15).
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:56][INFO] Waiting for graceful device shutdown. Hit Ctrl-C again to abort immediately.
[107171:internal-dpl-aod-reader]: [09:46:56][INFO] New state requested. No timeout set, quitting immediately as per --completion-policy
[107172:internal-dpl-aod-spawner]: [09:46:56][INFO] New state requested. No timeout set, quitting immediately as per --completion-policy
[107173:my-example-task]: [09:46:56][INFO] New state requested. No timeout set, quitting immediately as per --completion-policy
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:56][INFO] New state requested. No timeout set, quitting immediately as per --completion-policy
[107171:internal-dpl-aod-reader]: [09:46:56][STATE] RUNNING ---> READY
[107172:internal-dpl-aod-spawner]: [09:46:56][STATE] RUNNING ---> READY
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:56][STATE] RUNNING ---> READY
[107173:my-example-task]: [09:46:56][STATE] RUNNING ---> READY
[107171:internal-dpl-aod-reader]: [09:46:56][STATE] READY ---> RESETTING TASK
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:56][STATE] READY ---> RESETTING TASK
[107171:internal-dpl-aod-reader]: [09:46:56][STATE] RESETTING TASK ---> DEVICE READY
[107171:internal-dpl-aod-reader]: [09:46:56][STATE] DEVICE READY ---> RESETTING DEVICE
[107172:internal-dpl-aod-spawner]: [09:46:56][STATE] READY ---> RESETTING TASK
[107172:internal-dpl-aod-spawner]: [09:46:56][STATE] RESETTING TASK ---> DEVICE READY
[107173:my-example-task]: [09:46:56][STATE] READY ---> RESETTING TASK
[107173:my-example-task]: [09:46:56][STATE] RESETTING TASK ---> DEVICE READY
[107173:my-example-task]: [09:46:56][STATE] DEVICE READY ---> RESETTING DEVICE
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:56][STATE] RESETTING TASK ---> DEVICE READY
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:56][STATE] DEVICE READY ---> RESETTING DEVICE
[107172:internal-dpl-aod-spawner]: [09:46:56][STATE] DEVICE READY ---> RESETTING DEVICE
[107172:internal-dpl-aod-spawner]: [09:46:56][INFO] Cleaning up for shared memory id 'ab48176a'...
[107172:internal-dpl-aod-spawner]: [09:46:56][INFO] Found 0 unmanaged regions...
[107172:internal-dpl-aod-spawner]: [09:46:56][INFO] Found 1 managed segments...
[107172:internal-dpl-aod-spawner]: [09:46:56][INFO] Successfully removed 'fmq_ab48176a_m_0'.
[107172:internal-dpl-aod-spawner]: [09:46:56][INFO] Successfully removed 'fmq_ab48176a_mng'.
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:56][STATE] RESETTING DEVICE ---> IDLE
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:56][STATE] IDLE ---> EXITING
[107174:internal-dpl-aod-global-analysis-file-sink]: [09:46:56][STATE] Exiting FairMQ state machine
[107173:my-example-task]: [09:46:56][STATE] RESETTING DEVICE ---> IDLE
[107173:my-example-task]: [09:46:56][STATE] IDLE ---> EXITING
[107173:my-example-task]: [09:46:56][STATE] Exiting FairMQ state machine
[107171:internal-dpl-aod-reader]: [09:46:56][STATE] RESETTING DEVICE ---> IDLE
[107171:internal-dpl-aod-reader]: [09:46:56][STATE] IDLE ---> EXITING
[107171:internal-dpl-aod-reader]: [09:46:56][STATE] Exiting FairMQ state machine
[107172:internal-dpl-aod-spawner]: [09:46:56][STATE] RESETTING DEVICE ---> IDLE
[107172:internal-dpl-aod-spawner]: [09:46:56][STATE] IDLE ---> EXITING
[107172:internal-dpl-aod-spawner]: [09:46:56][STATE] Exiting FairMQ state machine
[INFO] ## Processes completed. Run summary:
[INFO] ### Devices started: 6
[INFO]  - Device internal-dpl-clock: pid 107170 (exit 0)
[INFO]  - Device internal-dpl-aod-reader: pid 107171 (exit 0)
[INFO]  - Device internal-dpl-aod-spawner: pid 107172 (exit 0)
[INFO]  - Device my-example-task: pid 107173 (exit 0)
[INFO]  - Device internal-dpl-aod-global-analysis-file-sink: pid 107174 (exit 0)
[INFO]  - Device internal-dpl-injected-dummy-sink: pid 107175 (exit 0)
[INFO] ## Analysis Run Summary ##
[INFO] ### Files read stats ###
[INFO] lfn=AO2D.root,size=2077790626,total_df=36,read_df=36,read_bytes=661276104,read_calls=669,io_time=6.2,wait_time=5.3,level=0
[INFO] Dumping used configuration in dpl-config.json
[O2Physics/latest] ~/alice/O2Physics/Tutorials/PWGMM $> ls
AnalysisResults.root  CMakeLists.txt   imgui.ini	  README.md
AO2D.root	      dpl-config.json  myExampleTask.cxx
[O2Physics/latest] ~/alice/O2Physics/Tutorials/PWGMM $> AnalysisResults.root
bash: AnalysisResults.root: command not found
[O2Physics/latest] ~/alice/O2Physics/Tutorials/PWGMM $> root
   ------------------------------------------------------------------
  | Welcome to ROOT 6.32.06                        https://root.cern |
  | (c) 1995-2024, The ROOT Team; conception: R. Brun, F. Rademakers |
  | Built for linuxx8664gcc on Oct 09 2024, 03:14:57                 |
  | From tags/v6-32-06-alice1@v6-32-06-alice1                        |
  | With c++ (GCC) 13.2.0                                            |
  | Try '.help'/'.?', '.demo', '.license', '.credits', '.quit'/'.q'  |
   ------------------------------------------------------------------

root [0] 
root [2] new TBrowser
(TBrowser *) 0x3ce5e90
root [3]
```

