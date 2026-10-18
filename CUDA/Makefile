
###----------------------------------------------------------------------------
NVCC=nvcc
# CUDA_FLAGS= --generate-code arch=compute_60,code=sm_60 -O3 #-DCUDA_DEBUG 

BINS= gpu_convol_v0   # 


###
all: ${BINS}

### gpu_convol_v* 
gpu_convol_v%: gpu_convol_v%.cu rasterfile.h
	${NVCC} ${CUDA_FLAGS} $< -o $@

####
clean: 
	rm -f ${BINS} *~ *.o 




