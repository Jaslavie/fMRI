Node: slicetime_correction (fsl)
================================


 Hierarchy : preproc_workflow.slicetime_correction
 Exec ID : slicetime_correction


Original Inputs
---------------


* args : <undefined>
* custom_order : <undefined>
* custom_timings : <undefined>
* environ : {'FSLOUTPUTTYPE': 'NIFTI'}
* global_shift : <undefined>
* in_file : /Users/jaslavie/fMRI/output/preproc_workflow/extract/roi_extracted.nii
* index_dir : <undefined>
* interleaved : True
* out_file : <undefined>
* output_type : NIFTI
* slice_direction : 3
* time_repetition : <undefined>


Execution Inputs
----------------


* args : <undefined>
* custom_order : <undefined>
* custom_timings : <undefined>
* environ : {'FSLOUTPUTTYPE': 'NIFTI'}
* global_shift : <undefined>
* in_file : /Users/jaslavie/fMRI/output/preproc_workflow/extract/roi_extracted.nii
* index_dir : <undefined>
* interleaved : True
* out_file : <undefined>
* output_type : NIFTI
* slice_direction : 3
* time_repetition : <undefined>


Execution Outputs
-----------------


* slice_time_corrected_file : /Users/jaslavie/fMRI/output/preproc_workflow/slicetime_correction/roi_extracted_st.nii


Runtime info
------------


* cmdline : slicetimer --in=/Users/jaslavie/fMRI/output/preproc_workflow/extract/roi_extracted.nii --odd --out=/Users/jaslavie/fMRI/output/preproc_workflow/slicetime_correction/roi_extracted_st.nii --direction=3
* duration : 10.687402
* hostname : Jasmines-MacBook-Air.local
* prev_wd : /Users/jaslavie/fMRI
* working_dir : /Users/jaslavie/fMRI/output/preproc_workflow/slicetime_correction


Terminal output
~~~~~~~~~~~~~~~


 


Terminal - standard output
~~~~~~~~~~~~~~~~~~~~~~~~~~


 


Terminal - standard error
~~~~~~~~~~~~~~~~~~~~~~~~~


 


Environment
~~~~~~~~~~~


* APPLICATION_INSIGHTS_NO_DIAGNOSTIC_CHANNEL : 1
* CLICOLOR : 1
* CLICOLOR_FORCE : 1
* COMMAND_MODE : unix2003
* CONDA_DEFAULT_ENV : base
* CONDA_EXE : /opt/miniconda3/bin/conda
* CONDA_PREFIX : /opt/miniconda3
* CONDA_PROMPT_MODIFIER : (base) 
* CONDA_PYTHON_EXE : /opt/miniconda3/bin/python
* CONDA_SHLVL : 1
* DISPLAY : /private/tmp/com.apple.launchd.mpQVO3Uc3Y/org.xquartz:0
* ELECTRON_NO_ATTACH_CONSOLE : 1
* ELECTRON_RUN_AS_NODE : 1
* FORCE_COLOR : 1
* FSLDIR : /usr/local/fsl
* FSLMULTIFILEQUIT : TRUE
* FSLOUTPUTTYPE : NIFTI
* FSLTCLSH : /Users/jaslavie/fsl/bin/fsltclsh
* FSLWISH : /Users/jaslavie/fsl/bin/fslwish
* FSL_LOAD_NIFTI_EXTENSIONS : 0
* FSL_SKIP_GLOBAL : 0
* GIT_PAGER : cat
* HOME : /Users/jaslavie
* HOMEBREW_CELLAR : /opt/homebrew/Cellar
* HOMEBREW_PREFIX : /opt/homebrew
* HOMEBREW_REPOSITORY : /opt/homebrew
* INFOPATH : /opt/homebrew/share/info:
* KMP_DUPLICATE_LIB_OK : True
* KMP_INIT_AT_FORK : FALSE
* LANG : en_US.UTF-8
* LESS : -R
* LOGNAME : jaslavie
* LSCOLORS : Gxfxcxdxbxegedabagacad
* LS_COLORS : di=1;36:ln=35:so=32:pi=33:ex=31:bd=34;46:cd=34;43:su=30;41:sg=30;46:tw=30;42:ow=30;43
* LaunchInstanceID : 865F87EE-22F8-45F2-B58E-67165C0739D4
* MPLBACKEND : module://matplotlib_inline.backend_inline
* MallocNanoZone : 0
* NVM_BIN : /Users/jaslavie/.nvm/versions/node/v20.11.0/bin
* NVM_CD_FLAGS : -q
* NVM_DIR : /Users/jaslavie/.nvm
* NVM_INC : /Users/jaslavie/.nvm/versions/node/v20.11.0/include/node
* ORIGINAL_XDG_CURRENT_DESKTOP : undefined
* PAGER : cat
* PATH : /usr/local/fsl/bin:/usr/local/fsl/bin:/usr/local/fsl/bin:/usr/local/fsl/bin:/Users/jaslavie/fMRI/venv/bin:/Users/jaslavie/.cargo/bin:/Users/jaslavie/.rye/shims:/opt/miniconda3/bin:/opt/miniconda3/condabin:/Users/jaslavie/.nvm/versions/node/v20.11.0/bin:/Users/jaslavie/fsl/share/fsl/bin:/Users/jaslavie/fsl/share/fsl/bin:/Library/Frameworks/Python.framework/Versions/3.11/bin:/opt/homebrew/bin:/opt/homebrew/sbin:/usr/local/bin:/System/Cryptexes/App/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin:/opt/X11/bin:~/.dotnet/tools:/Library/Apple/usr/bin:/Applications/quarto/bin:/Library/Frameworks/Mono.framework/Versions/Current/Commands
* PS1 : (venv) 
* PWD : /
* PYDEVD_IPYTHON_COMPATIBLE_DEBUGGING : 1
* PYDEVD_USE_FRAME_EVAL : NO
* PYTHONIOENCODING : utf-8
* PYTHONUNBUFFERED : 1
* PYTHON_FROZEN_MODULES : on
* SECURITYSESSIONID : 18da9
* SHELL : /bin/zsh
* SHLVL : 3
* SSH_AUTH_SOCK : /private/tmp/com.apple.launchd.SYHQEOOB6I/Listeners
* TERM : xterm-color
* TERM_PROGRAM : Apple_Terminal
* TERM_PROGRAM_VERSION : 447
* TERM_SESSION_ID : AE154C3B-5599-4C0C-9ECA-D287E2BD12A1
* TMPDIR : /var/folders/t4/kq2w5sp97l11x3ky8lqjsf800000gn/T/
* USER : jaslavie
* VIRTUAL_ENV : /Users/jaslavie/fMRI/venv
* VIRTUAL_ENV_PROMPT : (venv) 
* VSCODE_AMD_ENTRYPOINT : vs/workbench/api/node/extensionHostProcess
* VSCODE_CLI : 1
* VSCODE_CODE_CACHE_PATH : /Users/jaslavie/Library/Application Support/Cursor/CachedData/b1e87884330fc271d5eb589e368c35f14e76dec0
* VSCODE_CRASH_REPORTER_PROCESS_TYPE : extensionHost
* VSCODE_CWD : /Users/jaslavie/fMRI
* VSCODE_DOTNET_INSTALL_TOOL_ORIGINAL_HOME : /Users/jaslavie
* VSCODE_HANDLES_UNCAUGHT_ERRORS : true
* VSCODE_IPC_HOOK : /Users/jaslavie/Library/Application Support/Cursor/0.42-main.sock
* VSCODE_NLS_CONFIG : {"userLocale":"en-us","osLocale":"en","resolvedLanguage":"en","defaultMessagesFile":"/Applications/Cursor.app/Contents/Resources/app/out/nls.messages.json","locale":"en-us","availableLanguages":{}}
* VSCODE_PID : 81250
* XPC_FLAGS : 0x0
* XPC_SERVICE_NAME : 0
* ZSH : /Users/jaslavie/.oh-my-zsh
* _ : /Users/jaslavie/fMRI/venv/bin/python
* __CFBundleIdentifier : com.todesktop.230313mzl4w4u92
* __CF_USER_TEXT_ENCODING : 0x1F5:0x0:0x0

