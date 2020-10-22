medianFilter:
	[ -f $@ ] && rm $@ || echo "Done [binary]."
	[ -f "ship_out.png" ] && rm "ship_out.png" || echo "Done [png]."
	go build $@.go
	./$@ -in ship.png -out ship_out.png
