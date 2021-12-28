### Following SortedSet methods now return Java `List` instead of `Set`:

- zrange(byte[] key, long start, long stop)
- zrange(String key, long start, long stop)
- zrevrange(byte[] key, long start, long stop)
- zrevrange(String key, long start, long stop)
- zrangeWithScores(byte[] key, long start, long stop)
- zrangeWithScores(String key, long start, long stop)
- zrevrangeWithScores(byte[] key, long start, long stop)
- zrevrangeWithScores(String key, long start, long stop)
- zrandmember(byte[] key, long count)
- zrandmember(String key, long count)
- zrandmemberWithScores(byte[] key, long count)
- zrandmemberWithScores(String key, long count)
- zpopmax(byte[] key, int count)
- zpopmax(String key, int count)
- zpopmin(byte[] key, int count)
- zpopmin(String key, int count)
- zrangeByScore(byte[] key, double min, double max)
- zrangeByScore(String key, double min, double max)
- zrangeByScore(byte[] key, byte[] min, byte[] max)
- zrangeByScore(String key, String min, String max)
- zrevrangeByScore(byte[] key, double max, double min)
- zrevrangeByScore(String key, double max, double min)
- zrangeByScore(byte[] key, double min, double max, int offset, int count)
- zrangeByScore(String key, double min, double max, int offset, int count)
- zrevrangeByScore(byte[] key, byte[] max, byte[] min)
- zrevrangeByScore(String key, String max, String min)
- zrangeByScore(byte[] key, byte[] min, byte[] max, int offset, int count)
- zrangeByScore(String key, String min, String max, int offset, int count)
- zrevrangeByScore(byte[] key, double max, double min, int offset, int count)
- zrevrangeByScore(String key, double max, double min, int offset, int count)
- zrangeByScoreWithScores(byte[] key, double min, double max)
- zrangeByScoreWithScores(String key, double min, double max)
- zrevrangeByScoreWithScores(byte[] key, double max, double min)
- zrevrangeByScoreWithScores(String key, double max, double min)
- zrangeByScoreWithScores(byte[] key, double min, double max, int offset, int count)
- zrangeByScoreWithScores(String key, double min, double max, int offset, int count)
- zrevrangeByScore(byte[] key, byte[] max, byte[] min, int offset, int count)
- zrevrangeByScore(String key, String max, String min, int offset, int count)
- zrangeByScoreWithScores(byte[] key, byte[] min, byte[] max)
- zrangeByScoreWithScores(String key, String min, String max)
- zrevrangeByScoreWithScores(byte[] key, byte[] max, byte[] min)
- zrevrangeByScoreWithScores(String key, String max, String min)
- zrangeByScoreWithScores(byte[] key, byte[] min, byte[] max, int offset, int count)
- zrangeByScoreWithScores(String key, String min, String max, int offset, int count)
- zrevrangeByScoreWithScores(byte[] key, double max, double min, int offset, int count)
- zrevrangeByScoreWithScores(String key, double max, double min, int offset, int count)
- zrevrangeByScoreWithScores(byte[] key, byte[] max, byte[] min, int offset, int count)
- zrevrangeByScoreWithScores(String key, String max, String min, int offset, int count)
- zrangeByLex(byte[] key, byte[] min, byte[] max)
- zrangeByLex(String key, String min, String max)
- zrangeByLex(byte[] key, byte[] min, byte[] max, int offset, int count)
- zrangeByLex(String key, String min, String max, int offset, int count)
- zrevrangeByLex(byte[] key, byte[] max, byte[] min)
- zrevrangeByLex(String key, String max, String min)
- zrevrangeByLex(byte[] key, byte[] max, byte[] min, int offset, int count)
- zrevrangeByLex(String key, String max, String min, int offset, int count)