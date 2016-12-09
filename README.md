# Malware-Detection-using-Machine-Learning
Malware detection on Android devices using machine learning classification methods.
This repository is a proof of concept for malware detection on Android devices using behavioral features. 


## Data
Current data includes 100.000 samples apk samples.
Previous data is extracted from the proc virtual file system. data.csv file contains the process samples from Ubuntu Desktop environment.

## Features (For each apk)
Everything in an APK can be a feature. 
* hash
* milisecond
* state
* usage counter
* priority
* static priority
* normal priority
* policy
* vm_pgoff
* vm_truncate_count
* task_size
* cached_hole_size
* free_area_cache
* mm_users
* map_count
* hiwater_rss
* total_vm
* shared_vm
* exec_vm
* reserved_vm
* nr_ptes
* end_data
* last_interval
* nvcsw
* nivcsw
* min_flt
* maj_flt
* fs_excl_counter
* lock
* utime
* stime
* gtime
* cgtime
* signal_nvcsw

## TO-DO List
* Data extraction script will be pushed to the repository
* Feature selection algorithms will be applied for better results.
* More relevant features may be extracted from the kernel.
* A script will be written to do the whole process in real time at the user space.
* A kernel driver will be written to do the whole process in real time at the kernel level.

## Classification
There are many classification algorithms and libraries which can be used as a black box. We compared 3 different classification algorithms in the showcase which is an Ipython Notebook file. 
