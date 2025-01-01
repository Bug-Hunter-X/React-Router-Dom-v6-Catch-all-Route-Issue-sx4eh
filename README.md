This repository demonstrates a common issue encountered when using catch-all routes (`/*`) in React Router DOM v6. The problem arises when this catch-all route is placed after other more specific routes.  The solution involves reordering the routes so that the catch-all route is always the last one specified.