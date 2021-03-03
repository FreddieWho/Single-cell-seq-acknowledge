Tutorial for enclone

# group fields  
group_id: identifier of clonotype group  
group_ncells: total number of cells in the group  
# clonotype fields  
clonotype_id: identifier of clonotype within the clonotype group  
clonotype_ncells: total number of  cells in the clonotype  
nchains: total number of chains in the clonotype  
# chain fields, where \<i> is in clonotype above  
v/d/j_name\<i>:  
v/d/j_id\<i>:  
var_indices_dna/aa\<i>: DNA/amino acid position in chain that vary across the clonotype  
share_indices_dna/aa\<a>: DNA/amino acid position in chain that are constant across the clonotype but differ from the donor ref  
# exact subclonetype fields
exact_subclonotype_id: identifer of exact subclonotype  
barcodes:comma-separated list of barcodes for the exact subclonotype  
\<dataset>_barcodes: barcodes restricted to the dataset with the given name  
# chain ,exact subclonotype fields, where \<i> is in exact subclonotype above  

