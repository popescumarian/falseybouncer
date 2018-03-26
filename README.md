# falseybouncer
Remove all falsy values from an array.<br />
Falsy values in JavaScript are false, null, 0, "", undefined, and NaN.<br />
bouncer([7, "ate", "", false, 9]) should return [7, "ate", 9].<br />
bouncer(["a", "b", "c"]) should return ["a", "b", "c"].<br />
bouncer([false, null, 0, NaN, undefined, ""]) should return [].<br />
bouncer([1, null, NaN, 2, undefined]) should return [1, 2].<br />
