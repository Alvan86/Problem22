# Problem25 Final Exam, Fall 2022: Time Series Analysis of US Inflation (Useful in ISYE6042 HW)

Exercise 0 - (1 Points): Free point

Exercise 1 - (1 Points): cleanup_df(df, drop_cols), cells ' ' replaced with np.nan, col values converted to float64

Exercise 2 - (2 Points): Extract col values to a 2-D array > flatten to a 1-D array, handle the missing values

Exercise 3 - (2 Points): Return a Pandas Series with dtype of datetime64 containing the timestamp

Exercise 4 - (2 Points): Math formulaes

Exercise 5 - (2 Points): Math formulaes

Exercise 6 - (2 Points): Math formulaes

Exercise 7 - (3 Points): List of dictionaries, combinations, sort values based on lexographical order of each key

Exercise 8 - (3 Points): Algorithm > grid_search(func, ts, grid, n_back)

 
# Problem24 Final Exam, Spring 2022: March (through May) Madness


Exercise 0 - (1 Points) get_cols(conn) to return a list of the columns

Exercise 1 - (3 Points) UNION ALL, CASE WHEN ELSE, pd.concat() 

Exercise 2 - (1 Points) SQL

Exercise 3 - (3 Points) "window function" 

Exercise 4 - (2 Points) SQL 

Exercise 5 - (3 Points) "window function" 

Exercise 6 - (3 Points) Merging

Exercise 7 - (1 Points) pred_accuracy(obs, preds)

Exercise 8 - (2 Points) Calculating the bounds for each bucket and examine each pair of bounds


# Problem23 Final Exam: Fall 2021 - Housing Prices

Exercise 0: (1 point) Compute R2 Coefficient of determination - 1 - (SSR/SST)

Exercise 1: (1 point) Math formulaes

Exercise 2: (2 points) Cleaning the data (drop col/row, convert values to str, convert missing values to 0.0/None)

Exercise 3: (2 points) Log transformed values in the col, partition numerical/categorical col using select_dtypes

Exercise 4: (2 points) One-hot Encoding

Exercise 5: (2 points) def train_test_split(data, pct, splitter=ind_splitter)

Exercise 6: (3 points) Standardize the columns of X and compute its SVD

Exercise 7: (2 points) Linear regression


# Problem22 Spring 2021: Analyzing product reviews

Exercise 0 (2 points): Convert the reviews into a pandas data frame # Given a list of dictionaries, convert it to a pandas DataFrame object

Exercise 1 (2 points): Subselect e-books with usable genres # e-book - a string ID, 'genre' - a CLEANED genre string

Exercise 2 (1 point): Combining the data

Exercise 3 (2 points): Map string IDs to logical indices # Series object x > index and value x

Exercise 4 (2 points): Build a sparse matrix # def ratings_to_coo(ratings, r_map, e_map)

Exercise 5: Postprocessing the results (2 points)

Exercise 6: k-largest clusters (3 points)

Exercise 7: Top genres in each cluster (2 points)

Exercise 8 (last exercise!): Genre features (4 points)


# Problem 21: Final exam, Fall 2020: The legacy of "redlining"

Exercise 0: Filtering ratings (2 points) # filter_ratings(ratings, city_st, targets=None)

Exercise 1: Bounding box of all neighborhoods (3 points)

Exercise 2: Cleaning masked images (2 points)

Exercise 3: Average temperature (2 points)

Exercise 4: Cleaning the dataframe (2 points) # filter latest date col with regex

Exercise 5 (last one!): Merging price and geographic boundaries (2 points)


# Problem 20: Key sentences 

Exercise 0: Extracting sentences (2 points) # re.split, strip()

Exercise 1: Construct bags of words (2 points) 

Exercise 2: Constructing the coordinates for a sparse matrix (3 points)

Exercise 3: Ranking words (2 points) # def rank_words(u0, v0) >  argsort(u0)[::-1]

Exercise 4: Ranking sentences (1 point) # def rank_words(u0, v0) >  argsort(v0)[::-1]


# Problem 19: Click-through Balancing Act 

Exercise 0: Imputing missing values (2 points) # replace any missing values in each col by the mode or median

Exercise 1: Down-sampling (2 points) # Count # of 0 & 1 in array > determine the smaller group > get smaller indices > get subset indices > concat both

Exercise 2: Up-sampling (1 point)


# Problem 18: Data Jobs

Exercise 0 (2 points). # HTML results > pandas DataFrame

Exercise 1 (2 points). # filter_jobs(df, target_jobs) # target_jobs > list of substrings to match col

Exercise 2 (2 points). # Series containing the exact substring replaced with target

Exercise 3 (2 points) # Group by, median

Exercise 4 (2 points). # Iterate dict and use all previous functions for df summary


# Problem 17: Spectral graph partitioning (Useful in ISYE6740 HW)

Exercise 0 (2 points) # Given edges data frame, directed edge from node a to node b, symmetrize, also a directed edge b to a

Exercise 1 (1 point) # sparse matrix in coordinate (COO) format

Exercise 2 (2 points) # Return a pair of 1-D np contaning pos of all +ve entries and anothe for remaining

Exercise 3 (2 points) # invert_perm > argsort()

Exercise 4 (2 points) # Fiedler vector > permutation vector  > coordinate sparse matrix


# Problem 15: Semi-supervised Learning

Exercise 1 (2 points) # find_clusters(X, centers) using vq

Exercise 2 (1 point) # find_max_common_label_in_cluster(clustering, y, k)

Exercise 3 (2 points) # update_labels_1(y_train, X, centers)

Exercise 4 (1 point) # k_nearest_neighbor(X, img, k), Euclidean distance, argsort

Exercise 5 (1 point) # most_common_label(y_train, group)


# Problem 13: Traveling Salesperson Problem 

Exercise 0 (3 points) # total distance of a round-trip tour through the cities,  euclidean_distance

Exercise 1 (2 points) # swap_cities(path, i, j)

Exercise 2 (2 points) # acceptance_probability(old_distance, new_distance, k)

Exercise 3 (3 points)  # use all previous functions to implement full algorithm


# Problem 12: Snowball Poem Generator 

Exercise 0 (3 pts) # defaultdict mapping word len(n) > a set of all words following it len(n+1) # re.split

Exercise 1 (3 pts) # defaultdict maps word w to its longest "natural" run in the text (list)

Exercise 2 (4 pts) # Put it all together


# Problem 8: Counting triangles in a social network

Exercise 0 (3 points) # count_triangles(A) > int(np.sum(np.multiply(A.dot(A), A)) / 6)

Exercise 1 (2 points) # list > dict

Exercise 2 (2 points) # count_appearances(casts)

Exercise 3 (3 points) # build coords using combinations and convert to sparse matrix


# Problem 4

Exercise 0 (1 point) # read csv

Exercise 1 (1 point) # Euclidean distance(two-norm) # return a boolean Numpy array where X[i, :] lies within the eps-sized ball centered at p

Exercise 2 (1 point) # set_of_indices = set(np.where(y)[0])

Exercise 3 (1 point) # find_neighbors(eps, X[:m, :])

Exercise 4 (2 points) # find_core_points(s, neighbors)

Exercise 5 (4 points) # expand_cluster (p, neighbors, core_set, visited, assignment)


# Problem 2: "But her emails..."

Exercise 0 (1 point) # Read sql

Exercise 1 (3 points) # SQL query

Exercise 2 (3 points) # Merge data frame

Exercise 3 (3 points) # Merge data frame
