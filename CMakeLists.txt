add_library(RAxML SHARED axml.c optimizeModel.c multiple.c searchAlgo.c topologies.c parsePartitions.c treeIO.c models.c bipartitionList.c rapidBootstrap.c evaluatePartialGenericSpecial.c evaluateGenericSpecial.c newviewGenericSpecial.c makenewzGenericSpecial.c classify.c fastDNAparsimony.c fastSearch.c leaveDropping.c rmqs.c rogueEPA.c ancestralStates.c mem_alloc.c eigen.c)

target_link_libraries(RAxML m) 
