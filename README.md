# Street Manager - Reinstatement Mapping
Creates a map of reinstatements from a Street Manager download

I often get asked at work to identify the owner of some random reinstatement in the public highway, and as this isn't currently shown on Street Manager, it can be a hard task.  The mapping systems currently available to me are Street Manager itself and One Network, both of which show where a permit is pinned, not where reinstatements are registered.

At the end of 2024 I started to learn to code, and as a girl that likes a challenge, I picked this as a problem that I would like to solve - this is the result.  I fully expect that there are improvements that could be made to my code, so am open to suggestions! 

I've tried to write the code in such a way that I can easiliy reuse it to plot other things (S81s, inspections etc) without having to trawl through changing the names of the data frame and the columns.

The code could be expanded to show other things in the pop out boxes, but promoter and works reference suited my purposes. 

It will work with multiple USRNs, but I don't know if this will slow the map down - it will certainly look quite cluttered.

I've checked the html file (which can be downloaded and shared with other people) and there is nothing in there that wouldn't be open data, so this could have other uses, such as sharing locations maps with other departments, works promoters, Cllrs etc. 

# How to Use

You will need something like Jupyter notebooks and normal access to Street Manager (i.e. you don't need access to the admin settings).

1. Download the reinstatement data that you want from Street Manager (Registered Reinstatements)
2. Rename the file Reinstatements.csv (if you name it something else, you will need to change the pd.read_csv file name)
3. Run the code
4. Open/save the html file
