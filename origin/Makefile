# $(origin VARIABLE)


# undefined
$(info $(origin T))

# default
$(info $(origin MAKE))


# environment
$(info $(origin PATH))


# make -e  
# environment override
USER = LQL
$(info $(origin USER))

T := y

# file
$(info $(origin T))


# make CMD=1
# command line
$(info $(origin CMD))


# make CMD=1
# override
override CMD = 2
$(info $(origin CMD))


# automatic
all :
	$(info $(origin @))
