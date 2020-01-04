# androidVector2SVG
convert android resource xml vector file into svg file


# this is a modified of https://gitlab.com/alessandrolucchet/VectorDrawable2Svg
i added support for alpha color on vector file

# run
python convertVector2Svg.py [vectors files]
(the output file of svg file will be the same as vector file + .svg extension)
example: python convertVector2Svg.py /data/vectors/ic*.xml
