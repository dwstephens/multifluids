input: clean
	gmsh -2 src/mmat-gravity-col.geo
	../../scripts/gmsh2triangle --2d src/mmat-gravity-col.msh

clean:
	rm -rf *.d.* *.stat *.vtu *.convergence mmat-gravity-col.node mmat-gravity-col.edge mmat-gravity-col.ele src/set_phi *checkpoint* *.log-0 *.err-0 matrixdump*
