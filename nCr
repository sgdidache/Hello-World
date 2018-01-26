def num_combination(n, m):
    """Calculates number of ways to choose m items from a set of n distinct items"""
    if n<1 or n<m:
        return 0    # no way to choose if there are no items (n<1), or if there are not enough items to choose from (n<m)
    elif n==1:
        return 1
    else:
        return n + num_combination(n-1, m-1)
