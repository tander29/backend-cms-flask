<!-- user only gets 1 profile? -->

Primary key = underline
Foreign key = bold
Composite key = bold and underline

User (id, role_id
Profile(id, user_id, body, avatar
Roles (id, title
Permissions(id, title,
Role_permissions(role_id, permissions_id
UserPublishedPages (user_id, page_id
Pages (id, user_id, publish_status
Category (id, category_title
Category_Parent(category_id, category_parent_id
Tags(id, body
TaggedPages(page_id, tag_id
PagesContributors(pages_id, user_id
PageCategories (pages_id, category_id
FlagReview (id, pages_id)

Role title: (admin, user, contributor)
Permissions title: (read, write,constribute, delete, multiple_profile, can_flag)
