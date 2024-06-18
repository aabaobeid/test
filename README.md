# test

ontario_population <-
  get_census(
    dataset = "CA16",
    level = "Regions",
    vectors = "v_CA16_1",
    regions = list(PR = c("35"))
  )
  
ontario_population

