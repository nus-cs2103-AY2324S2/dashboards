%%[This page was last updated on Apr 14 2023]%% [**<span class="text-warning">:octicon-eye:</span> indicates those _watching_ the forum** (kudos :+1:)]


<panel type="info" header="### 1. VU V..DUNG `@joulev` (21 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: How to set up auto-format on save/commit in IntelliJ?**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/36" expanded>

I use VSCode, and have been able to configure auto-format on save in my editor, so I never have to worry about formatting &ndash; Ctrl+S and my file is nicely formatted according to the style guide. In fact it's hard to go *against* the style guide since the formatter is run on save.

However, all other members of my team are using the recommended IDE &ndash; IntelliJ, and from my observation in their PRs, they are apparently formatting the Java files *manually, by hand*. That's troublesome and, needless to say, prone to human errors (my editor has been able to detect several formatting issues, from spacing to max line width, just by re-saving the files alone).

But IntelliJ is well-known to be a powerful IDE, there's no way it doesn't have an auto-formatter built-in, right? I want to help my teammates to set up their environments so that formatting is never an issue again, but I don't have IntelliJ. So here comes the question:

**How to set up an auto-formatter in IntelliJ, that can automatically format the Java file on save/commit according to the style guide?**

<details>
<summary>For reference, this is how I set up the auto-formatter in VSCode.</summary>

Install the Java extension pack.

Add the following files to the root of your project (you can add `.vscode` to `.gitignore` if you want):

**`.vscode/settings.json`**

```json
{
  "editor.formatOnSave": true,
  "java.format.settings.url": ".vscode/java-formatter.xml",
}
```

**`.vscode/java-formatter.xml`** (don't ask me, I pasted this from Google)

```xml
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<profiles version="20">
    <profile kind="CodeFormatterProfile" name="JavaConventions" version="20">
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_ellipsis" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_enum_declarations" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_allocation_expression" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_at_in_annotation_type_declaration" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.parentheses_positions_in_for_statment" value="common_lines"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.new_lines_at_block_boundaries" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_logical_operator" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_constructor_declaration_parameters" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.insert_new_line_for_parameter" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_after_annotation_on_package" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.parentheses_positions_in_method_invocation" value="common_lines"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_between_empty_parens_in_enum_constant" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.blank_lines_after_imports" value="1"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_while" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.insert_new_line_before_root_tags" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_between_empty_parens_in_annotation_type_member_declaration" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.parentheses_positions_in_record_declaration" value="common_lines"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_method_declaration_throws" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.parentheses_positions_in_switch_statement" value="common_lines"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.format_javadoc_comments" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.indentation.size" value="4"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_postfix_operator" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.parentheses_positions_in_enum_constant_declaration" value="common_lines"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_for_increments" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_type_arguments" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_arrow_in_switch_default" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_for_inits" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_semicolon_in_for" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.align_with_spaces" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.disabling_tag" value="@formatter:off"/>
        <setting id="org.eclipse.jdt.core.formatter.continuation_indentation" value="2"/>
        <setting id="org.eclipse.jdt.core.formatter.number_of_blank_lines_before_code_block" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_switch_case_expressions" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_enum_constants" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.blank_lines_before_imports" value="1"/>
        <setting id="org.eclipse.jdt.core.formatter.number_of_blank_lines_at_end_of_method_body" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.blank_lines_after_package" value="1"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_multiple_local_declarations" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.parentheses_positions_in_if_while_statement" value="common_lines"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_arguments_in_enum_constant" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_angle_bracket_in_parameterized_type_reference" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.indent_root_tags" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.wrap_before_or_operator_multicatch" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.enabling_tag" value="@formatter:on"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_closing_brace_in_block" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.count_line_length_from_starting_position" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_record_components" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_parenthesized_expression_in_return" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_throws_clause_in_method_declaration" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_after_annotation_on_parameter" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_arrow_in_switch_case" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.wrap_before_multiplicative_operator" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_then_statement_on_same_line" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_after_annotation_on_field" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_explicitconstructorcall_arguments" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_prefix_operator" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.blank_lines_between_type_declarations" value="1"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_brace_in_array_initializer" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_for" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_catch" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_angle_bracket_in_type_arguments" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_after_annotation_on_method" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_switch" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_parameterized_type_references" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_anonymous_type_declaration" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_logical_operator" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_parenthesized_expression" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_annotation_declaration_on_one_line" value="one_line_never"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_record_declaration" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_after_annotation_on_enum_constant" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_multiplicative_operator" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.never_indent_line_comments_on_first_column" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_and_in_type_parameter" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_for_inits" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.indent_statements_compare_to_block" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.brace_position_for_anonymous_type_declaration" value="end_of_line"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_question_in_wildcard" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_annotation" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_method_invocation_arguments" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_switch" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.align_tags_descriptions_grouped" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.line_length" value="80"/>
        <setting id="org.eclipse.jdt.core.formatter.use_on_off_tags" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_method_body_on_one_line" value="one_line_never"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_between_empty_brackets_in_array_allocation_expression" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_loop_body_block_on_one_line" value="one_line_never"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_enum_constant" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_between_empty_parens_in_method_invocation" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_assignment_operator" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_type_declaration" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_for" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.preserve_white_space_between_code_and_line_comments" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_after_annotation_on_local_variable" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.brace_position_for_method_declaration" value="end_of_line"/>
        <setting id="org.eclipse.jdt.core.formatter.blank_lines_before_abstract_method" value="1"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_enum_constant_declaration_on_one_line" value="one_line_never"/>
        <setting id="org.eclipse.jdt.core.formatter.align_variable_declarations_on_columns" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_method_invocation" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_union_type_in_multicatch" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_colon_in_for" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_type_declaration_on_one_line" value="one_line_never"/>
        <setting id="org.eclipse.jdt.core.formatter.number_of_blank_lines_at_beginning_of_method_body" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_closing_angle_bracket_in_type_arguments" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_else_statement_on_same_line" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.parentheses_positions_in_catch_clause" value="common_lines"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_additive_operator" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_parameterized_type_reference" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_array_initializer" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_multiple_field_declarations" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_annotation" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_record_constructor" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_arguments_in_explicit_constructor_call" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_relational_operator" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_multiplicative_operator" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_anonymous_type_declaration_on_one_line" value="one_line_never"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_switch_case_expressions" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.wrap_before_shift_operator" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.indent_body_declarations_compare_to_annotation_declaration_header" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_superinterfaces" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_record_declaration_on_one_line" value="one_line_never"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_colon_in_default" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_question_in_conditional" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.brace_position_for_block" value="end_of_line"/>
        <setting id="org.eclipse.jdt.core.formatter.brace_position_for_constructor_declaration" value="end_of_line"/>
        <setting id="org.eclipse.jdt.core.formatter.brace_position_for_lambda_body" value="end_of_line"/>
        <setting id="org.eclipse.jdt.core.formatter.number_of_blank_lines_at_end_of_code_block" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.compact_else_if" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_type_parameters" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_catch" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_method_invocation" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_bitwise_operator" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.put_empty_statement_on_new_line" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_parameters_in_constructor_declaration" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_type_parameters" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_method_invocation_arguments" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_arguments_in_method_invocation" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_throws_clause_in_constructor_declaration" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_compact_loops" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.clear_blank_lines_in_block_comment" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_before_catch_in_try_statement" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_try" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_simple_for_body_on_same_line" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_at_end_of_file_if_missing" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.clear_blank_lines_in_javadoc_comment" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_relational_operator" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_array_initializer" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_unary_operator" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_expressions_in_array_initializer" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.format_line_comment_starting_on_first_column" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.number_of_empty_lines_to_preserve" value="1"/>
        <setting id="org.eclipse.jdt.core.formatter.parentheses_positions_in_annotation" value="common_lines"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_colon_in_case" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_ellipsis" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_additive_operator" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_semicolon_in_try_resources" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_colon_in_assert" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_if" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_type_arguments" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_and_in_type_parameter" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_string_concatenation" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_parenthesized_expression" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.format_line_comments" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.brace_position_for_record_declaration" value="end_of_line"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_colon_in_labeled_statement" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.text_block_indentation" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.align_type_members_on_columns" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_assignment" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_module_statements" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.indent_body_declarations_compare_to_type_header" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_between_empty_parens_in_method_declaration" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.number_of_blank_lines_after_code_block" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.align_tags_names_descriptions" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_enum_constant" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_superinterfaces_in_type_declaration" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_if_then_body_block_on_one_line" value="one_line_never"/>
        <setting id="org.eclipse.jdt.core.formatter.blank_lines_before_first_class_body_declaration" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_conditional_expression" value="80"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_before_closing_brace_in_array_initializer" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_constructor_declaration_parameters" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.format_guardian_clause_on_one_line" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_if" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.align_assignment_statements_on_columns" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_after_annotation_on_type" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_block" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.brace_position_for_enum_declaration" value="end_of_line"/>
        <setting id="org.eclipse.jdt.core.formatter.brace_position_for_block_in_case" value="end_of_line"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_arrow_in_switch_default" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_constructor_declaration" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.insert_new_line_between_different_tags" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_conditional_expression_chain" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.format_header" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_arguments_in_allocation_expression" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.wrap_before_assertion_message_operator" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_additive_operator" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_method_invocation" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_while" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_switch" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_method_declaration" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.join_wrapped_lines" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_between_empty_parens_in_constructor_declaration" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.wrap_before_conditional_operator" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.indent_switchstatements_compare_to_cases" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_bracket_in_array_allocation_expression" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_synchronized" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_shift_operator" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.align_fields_grouping_blank_lines" value="2147483647"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.new_lines_at_javadoc_boundaries" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_bitwise_operator" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.brace_position_for_annotation_type_declaration" value="end_of_line"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_colon_in_for" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_resources_in_try" value="80"/>
        <setting id="org.eclipse.jdt.core.formatter.use_tabs_only_for_leading_indentations" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.parentheses_positions_in_try_clause" value="common_lines"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_selector_in_method_invocation" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.never_indent_block_comments_on_first_column" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_code_block_on_one_line" value="one_line_never"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_synchronized" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_constructor_declaration_throws" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_record_components" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.tabulation.size" value="8"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_bitwise_operator" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_allocation_expression" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_bracket_in_array_reference" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_colon_in_conditional" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.format_source_code" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_array_initializer" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_try" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_semicolon_in_try_resources" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.blank_lines_before_field" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_at_in_annotation" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.continuation_indentation_for_array_initializer" value="2"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_question_in_wildcard" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.blank_lines_before_method" value="1"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_superclass_in_type_declaration" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_record_declaration" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_superinterfaces_in_enum_declaration" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_parenthesized_expression_in_throw" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.wrap_before_assignment_operator" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_colon_in_labeled_statement" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_not_operator" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.brace_position_for_switch" value="end_of_line"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_superinterfaces" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_method_declaration_parameters" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_after_type_annotation" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_brace_in_array_initializer" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_parenthesized_expression" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.format_html" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_at_in_annotation_type_declaration" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_closing_angle_bracket_in_type_parameters" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.parentheses_positions_in_method_delcaration" value="common_lines"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_compact_if" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_lambda_body_block_on_one_line" value="one_line_never"/>
        <setting id="org.eclipse.jdt.core.formatter.indent_empty_lines" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_type_arguments" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_parameterized_type_reference" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_unary_operator" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_enum_constant" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_arguments_in_annotation" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_enum_declarations" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_record_constructor_on_one_line" value="one_line_never"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_record_declaration" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_empty_array_initializer_on_one_line" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.indent_switchstatements_compare_to_switch" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_assertion_message" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_before_else_in_if_statement" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_assignment_operator" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_constructor_declaration" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.blank_lines_before_new_chunk" value="1"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_after_label" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.indent_body_declarations_compare_to_enum_declaration_header" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_bracket_in_array_allocation_expression" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_constructor_declaration" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_colon_in_conditional" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_angle_bracket_in_parameterized_type_reference" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_method_declaration_parameters" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_angle_bracket_in_type_arguments" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_cast" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_arrow_in_switch_case" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_colon_in_assert" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.blank_lines_before_member_type" value="1"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_before_while_in_do_statement" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_logical_operator" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_bracket_in_array_type_reference" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.indent_body_declarations_compare_to_record_header" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_angle_bracket_in_parameterized_type_reference" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_arguments_in_qualified_allocation_expression" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_superinterfaces_in_record_declaration" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_after_opening_brace_in_array_initializer" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.indent_breaks_compare_to_cases" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_method_declaration" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.wrap_before_bitwise_operator" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_if" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_semicolon" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.wrap_before_relational_operator" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_postfix_operator" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_try" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_angle_bracket_in_type_arguments" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_cast" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.format_block_comments" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_lambda_arrow" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_method_declaration" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.indent_tag_description" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_imple_if_on_one_line" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.brace_position_for_record_constructor" value="end_of_line"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_enum_declaration" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_parameters_in_method_declaration" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_between_brackets_in_array_type_reference" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_angle_bracket_in_type_parameters" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_string_concatenation" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_semicolon_in_for" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_method_declaration_throws" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_bracket_in_array_allocation_expression" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.blank_lines_after_last_class_body_declaration" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.indent_statements_compare_to_body" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_multiple_fields" value="16"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_enum_constant_arguments" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_simple_while_body_on_same_line" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_prefix_operator" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.brace_position_for_array_initializer" value="end_of_line"/>
        <setting id="org.eclipse.jdt.core.formatter.wrap_before_logical_operator" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_shift_operator" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_method_declaration" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_type_parameters" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_catch" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.blank_lines_between_statement_group_in_switch" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_bracket_in_array_reference" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_comma_in_annotation" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_enum_constant_arguments" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.parentheses_positions_in_lambda_declaration" value="common_lines"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_shift_operator" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_between_empty_braces_in_array_initializer" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_colon_in_case" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_multiple_local_declarations" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_simple_do_while_body_on_same_line" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_annotation_type_declaration" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_bracket_in_array_reference" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_enum_declaration_on_one_line" value="one_line_never"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_record_components" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_method_declaration" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.wrap_outer_expressions_when_nested" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_closing_paren_in_cast" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.brace_position_for_enum_constant" value="end_of_line"/>
        <setting id="org.eclipse.jdt.core.formatter.brace_position_for_type_declaration" value="end_of_line"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_multiplicative_operator" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.blank_lines_before_package" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_for" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_synchronized" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_for_increments" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_annotation_type_member_declaration" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.alignment_for_expressions_in_for_loop_header" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.wrap_before_additive_operator" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.keep_simple_getter_setter_on_one_line" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_while" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_enum_constant" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_explicitconstructorcall_arguments" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_paren_in_annotation" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_angle_bracket_in_type_parameters" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.indent_body_declarations_compare_to_enum_constant_header" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_string_concatenation" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_lambda_arrow" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_brace_in_constructor_declaration" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_constructor_declaration_throws" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.join_lines_in_comments" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_closing_angle_bracket_in_type_parameters" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_question_in_conditional" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.comment.indent_parameter_description" value="false"/>
        <setting id="org.eclipse.jdt.core.formatter.number_of_blank_lines_at_beginning_of_code_block" value="0"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_new_line_before_finally_in_try_statement" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_record_declaration" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.tabulation.char" value="mixed"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_relational_operator" value="insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_comma_in_multiple_field_declarations" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.wrap_before_string_concatenation" value="true"/>
        <setting id="org.eclipse.jdt.core.formatter.blank_lines_between_import_groups" value="1"/>
        <setting id="org.eclipse.jdt.core.formatter.lineSplit" value="100"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_after_opening_paren_in_annotation" value="do not insert"/>
        <setting id="org.eclipse.jdt.core.formatter.insert_space_before_opening_paren_in_switch" value="insert"/>
    </profile>
</profiles>
```

</details>
</panel>

<panel  header="**2. :fas-info-circle: Do I need to create a branch for all A-* tags after A-Packages?**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/25" expanded>

<img width="714" alt="image" src="https://user-images.githubusercontent.com/44609036/216802299-0cabe95b-05fb-4bba-9e4a-80f6c7cef3cc.png">

From the screenshot I see that creating `branch-A-Packages` is only recommended, not *required* (hence I didn't do it).

However, does the same apply for future `A-*` tags? Or do I need to create branches for each of those tags?
</panel>

<panel  header="**3. :fas-info-circle: How do I submit solutions for questions from 2 onwards on Coursemology?**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2" expanded>

<img width="559" alt="image" src="https://user-images.githubusercontent.com/44609036/212438944-3c2084ce-954d-40ab-97c4-577fced65ef4.png">

When I attempted it, the numbers from 2 to 4 were greyed out and could not be clicked on. In the many buttons down below, none of them contains the text like "Move to next question" either. It made me think the quiz only has one question, which I know is wrong once I submitted the attempt.

So what should I do to submit code for question 2 onwards?

If someone hasn't attempted, could you add a screenshot of that here as well (I have submitted so I cannot go back to that screen anymore).

&gt;!-- Can someone just redesign this panel? The whole interface is quite confusing to use. -->

Edit: If you didn’t receive the invitation link, see #3.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/1#issuecomment-1377399807" expanded>

A minor bug, but when I use the search box, there is additional spacing around the highlighted sections inside the search results.

<img width="400" alt="image" src="https://user-images.githubusercontent.com/44609036/211583608-ca18fafc-372b-4350-a38c-e0675fb5b2b2.png">

So in the above example, in the first search result it should be displayed as "**Hel**p" instead of "**Hel** p".
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/3#issuecomment-1382636400" expanded>

It went to my spam folder yesterday at 22:50. You might want to check your NUS email spam folder.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/5#issuecomment-1383090072" expanded>

> Consequently, once we finalize the submission (at least for me), the grade received is only 3.0/4/0 because question 2 is 0.0/1.0. Is it meant to be that way?

@mitchmalvin1 For my case (didn’t do question 2 onwards, ref #2), the system counted 0 passes/0 tests for question 2 as AC for some reasons, so I still got 2/4.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/6#issuecomment-1383122570" expanded>

When running `git log` locally it will show the history of all commits, could you paste the recent commits here so we know how your local history is like? Also could you paste the output of `git status` as well?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/6#issuecomment-1383143415" expanded>

Alright, from the output of `git status`, your local branch has diverged from the remote (GitHub) branch. Your tree currently looks like this

```
old commits ─── previous commit ─── current commit (remote)
                      │
                      └──────────── current commit (local)
```

I also went to see your repository; your remote repository latest commit hash is `1f347c886abfbee97a1037d425de8f57b583054e` while your local repository latest commit hash is `1ee7646a757d98ec4302d3d39b000e64d849d87b`, confirming the above.

Now what to do? Normally people would probably merge the upstream to their local repo. But in this case, I don't think a merge is necessary (we haven't even studied about it yet). Instead, you probably want to *force* push/pull to discard one version and keep the other.

To discard the remote version (your remote commit will be gone), use `git push --force`.

To discard the local version (your local commit will be gone), use `git reset --hard origin/master`.

After these commands, the local repo will be synced to the remote repo, and you can then `git push` or `git pull` normally.

Please note that `--force` and `--hard` are dangerous and generally discouraged. Especially `git push --force`, don’t use it for team (>1 person) projects. However, they can be used for cases like the one described here. Please remember to read their documentation as well.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1383161275" expanded>

Hi everyone, perhaps it’s a bit late by now already, but [it’s a bad idea to comment “+1” or “same problem” or similar](https://github.com/orgs/community/discussions/4921) in GitHub issues. Please use reactions (emotes) instead.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1383627767" expanded>

@okkhoy My full name is Vu Van Dung. Thank you.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/8#issuecomment-1398485598" expanded>

My two cents:

* While the "Generate new token (classic)" page works, the newer "Generate new token" works just as well, while also having a more intuitive interface (no more of those confusing checkboxes).

* For "Generate new token (classic)", you only need to check the "repo" box at the top to get push access. No need of "workflow" and so on.

* However, I recommend [authenticating with SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh) instead, no more pasting the token every time you need to make a push. It shouldn't take more than a few minutes to set this up (just copy all the commands in the linked page, really, and paste them to the terminal). If you are from CEG, [we already learned about SSH](https://nus-cs1010.github.io/2122-s1/environments.html#setting-up-ssh-keys) in CS1010.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/8#issuecomment-1401414760" expanded>

> @joulev 
> 
> > For "Generate new token (classic)", you only need to check the "repo" box at the top to get push access. No need of "workflow" and so on.
> 
> 
> 
> **No need of "workflow" and so on.** Sure this works? 
> 

I haven't generated a token for a long time so I am not 100% sure, but I'm like 95% sure that the "workflow" option is for interacting with GitHub Actions and similar, and is not required for push access.

To be absolutely sure, it's best to consult the documentation at https://docs.github.com but as I'm on mobile right now... sorry I can't link the specific page here.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/12#issuecomment-1401736758" expanded>

Per https://stackoverflow.com/a/9529518 you need to use either `origin` or `https://github.com/nikkiDEEE/ip.git`. It’s pretty clear which one is better.

Of course assuming you haven’t renamed your default aliases which you probably shouldn’t do for our course.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/8#issuecomment-1401771417" expanded>

I just checked the documentation and as written in [here](https://docs.github.com/en/developers/apps/building-oauth-apps/scopes-for-oauth-apps#available-scopes),

* `repo` is sufficient to get read and write access, hence is sufficient for `git push`.

* `workflow` is for interacting with GitHub Actions workflows, which is a form of CI. For now we don't need it, later in the course it might or might not be necessary when we learn CI? (@okkhoy could you confirm this?)

For `workflow` this sentence is interesting:

> Workflow files can be committed without [`workflow`] if the same file (with both the same path and contents) exists on another branch in the same repository.

Once again, I *really* recommend everyone to spend 10 minutes setting up SSH so that you don't have to deal with all this mess.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/8#issuecomment-1401920345" expanded>

> Thanks! I suppose in my case, since I handle repositories in another module that involves CI, it requires me to setup all these permissions (though I dun remember when I set it up).

I think from the sentence in the documentation, if you need to create a new workflow or delete a workflow (`.github/workflows/*.yml`), you need the `workflow` permission. But if you create or delete the file using the GitHub UI (on github dot com) for example, you can then edit the workflows locally without the `workflow` permission.

Later on if we will use GitHub Actions for continuous integration, then it is indeed necessary to use `workflow` to avoid weird errors that GitHub will give.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1402073967" expanded>

Since we are at week 3 and can access Week 4 quiz already, I will close this issue. Anyone having issues with the submissions are still welcome to post messages here but I doubt there is anyone like that now.
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/16#issuecomment-1407399346" expanded>

Off topic but @tangphi FYI you can format code using *code fences* &gt;code>'''&gt;/code> like this

&gt;pre>&gt;code>'''java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, world!");
    }
}
'''&gt;/code>&gt;/pre>

giving the output

'''java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, world!");
    }
}
'''
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/13#issuecomment-1407955896" expanded>

@okkhoy Basically, if I understand this discussion correctly, this means we can define the input in any way we want, as long as the user can perform the actions defined in each level. Am I correct?
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/25#issuecomment-1416924061" expanded>

From [this](https://nus-cs2113-ay2223s1.github.io/dashboards/contents/ip-progress.html) (last sem dashboard)

<img width="785" alt="image" src="https://user-images.githubusercontent.com/44609036/216802705-d23a0ca3-9a56-4d5f-b1ac-dfb65f6d09e0.png">

I suppose some tags require branches while some tags don't.
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/25#issuecomment-1418508825" expanded>

Understood, thank you.
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/36#issuecomment-1465469467" expanded>

@woowenjun99 A commit hook is always possible but it would be an overkill.

@nichyjt Thanks, I think this is it. I'll ask my teammates to set it up.
</panel>

</panel>


<panel type="info" header="### 2. WOO .. JUN `@woowenjun99` (9 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Alternate Arrangement For PE**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/48" expanded>

Hi prof, can I check with you what the alternative arrangement for the PE is if we are unwell and have a MC on that day?

I understand there is a remote option, but if we are not up to performance that day, do we still take the exam? Or will there be a make up PE?
</panel>

<panel  header="**2. :fas-info-circle: Cannot Access Catcher**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/40" expanded>

I tried to re-enter catcher with the same GitHub account and they asked if I want to continue as my GitHub account which I clicked, but it showed that I am an unauthorised user. Does this mean that I will not be able to edit the catcher again after the smoke test is done?

<img width="683" alt="Screenshot 2023-03-24 at 9 53 55 AM" src="https://user-images.githubusercontent.com/88195289/227404731-f4df2763-23cb-4d45-bb00-b088f5650245.png">

</panel>

<panel  header="**3. :fas-info-circle: Your earpiece is with me**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/30" expanded>

To the guy who was sitting on the right side of the LT during the lecture, your black earpiece is with me. Please collect it from me
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/16#issuecomment-1407394745" expanded>

Is it possible to send the code here as some of us did not encounter this issue, and thus difficult to debug
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/16#issuecomment-1407398445" expanded>

Try removing additional \n in the println in printArea?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/21#issuecomment-1413058531" expanded>

I have cloned your project and ran the command `sh runtest.sh` on my M1 laptop and received the following in my ACTUAL.txt. 

```bash
██████╗  █████╗ ██████╗  █████╗ 
██╔══██╗██╔══██╗██╔══██╗██╔══██╗
██████╔╝███████║██████╔╝███████║
██╔═══╝ ██╔══██║██╔═══╝ ██╔══██║
██║     ██║  ██║██║     ██║  ██║
╚═╝     ╚═╝  ╚═╝╚═╝     ╚═╝  ╚═╝
================================
Hello! I'm PAPA, your Personal Assistant, Personal Angel.
What can I do for you? Type 'help' for a list of commands.
================================
> 
```

Can you list down the steps to reproduce the issue?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/21#issuecomment-1413107707" expanded>

I had tried again and I received the `???` in the IntelliJ's in-built terminal but when I run the programme on VSC terminal and macbook's own terminal, I am able to print out the output as shown in the `ACTUAL.txt`. 

Can you try checking whether you are able to do the same? Run the java file on the intellij terminal, then other terminal such as VSC's or your computer's? If it is, then it is probably the issue to do with IntelliJ's terminal and not the encoding.

Image 1: IntelliJ Terminal
Image 2: VSC Terminal

<img width="691" alt="Screenshot 2023-02-02 at 11 33 33 AM" src="https://user-images.githubusercontent.com/88195289/216225592-7af570f0-d5a8-4fd5-83ef-11ff808f72b0.png">

<img width="504" alt="Screenshot 2023-02-02 at 11 33 45 AM" src="https://user-images.githubusercontent.com/88195289/216225593-4140ebc7-3d53-41eb-a081-4706f7cb5768.png">


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/34#issuecomment-1463500291" expanded>

1. Make these variables non-static if they only apply to the `Chicken` subclass.
2. Create a subclass of `Bird` that extends `Animal` and have the static variables stored in them. 
3. Create a class of meta data that keeps track of the data.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/36#issuecomment-1465348359" expanded>

Prof Akshay covered it during the lecture when he went through how to set up the auto-formatter for the switch case. It is under Settings --> Code Style --> Java. Following which, your group mate can go to keymap to edit the keys that is required to activate the formatter. The default command that he uses is Command + Option + L (same for me). Do ask him to review it.

As for on save/commit... Maybe you might want to set up a pre-push hook that runs the CI `./gradlew check` locally upon every git push. It will definitely slow down development, but it checks whether the coding style is followed in every file and ensures that all the test passes upon every push. 

(Edit: The test will fail when the style is not followed. Ask the person to go and fix the style manually with Command Option L)

Frankly speaking, the Auto Formatter is the only reason why I am using IntelliJ instead of VSCode. 
</panel>

</panel>


<panel type="info" header="### 3. CHOO..HONG `@choongzhanhong` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: text-ui-testing: how to overcome Unmappable Character for Encoding**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/21" expanded>

Hi, all. I recently ran into an issue with running the automated testing batch file, with the error relating to encoding a string I had printed.
For context, I named my version of Duke "PAPA" and gave it a new logo.
```
public static final String MESSAGE_LOGO =
            "██████╗  █████╗ ██████╗  █████╗ \n" +
            "██╔══██╗██╔══██╗██╔══██╗██╔══██╗\n" +
            "██████╔╝███████║██████╔╝███████║\n" +
            "██╔═══╝ ██╔══██║██╔═══╝ ██╔══██║\n" +
            "██║     ██║  ██║██║     ██║  ██║\n" +
            "╚═╝     ╚═╝  ╚═╝╚═╝     ╚═╝  ╚═╝";
```

I had trouble compiling and running (Although it runs fine in IntelliJ), and it turns out to be due to the uncommon characters being used. After looking up on stackoverflow, it seems adding the flag `-encoding ISO-8859-1` allows the files to compile and the batch file to run.

Now, here's what it outputs on the ACTUAL.txt output file:
```
â??â??â??â??â??â??â??  â??â??â??â??â??â?? â??â??â??â??â??â??â??  â??â??â??â??â??â?? 
â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??
â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??â??
â??â??â??â??â??â??â?? â??â??â??â??â??â??â??â??â??â??â??â??â??â??â?? â??â??â??â??â??â??â??â??
â??â??â??     â??â??â??  â??â??â??â??â??â??     â??â??â??  â??â??â??
â??â??â??     â??â??â??  â??â??â??â??â??â??     â??â??â??  â??â??â??
```

Now, it seems a minor issue since it's not something I need to do testing on, but is there a proper way to address this issue and to make sure it outputs correctly onto the .txt file?
</panel>

<panel  header="**2. :fas-info-circle: 💡 Coursemology Week 3 Question 10: Ex10**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/9" expanded>

Hi folks, this was originally supposed to be a help request for [Ex10](https://nus-cs2113-ay2223s2.github.io/website/schedule/week3/topics.html#key-exercise-find-total-expenditure), but I found the solution while writing this, so I'm sharing with the rest of you.

Note that the desired output is this:
'Your expenses while overseas?Expenses in overseas currency:[$4.50, $3.00, $5.00]
Total in local currency: $21.25'

The skeleton code does not use 'println' but instead uses 'print' (Does not automatically go to a newline). Also note there is no space between '"Expenses in overseas currency:"' and your array. These have to match the output on Coursemology to be considered correct.

Honestly, the desired output is not very nice because of inconsistent spacing, but oh well. Coursemology asks, I give.
</panel>

<panel  header="**3. :fas-info-circle: Trouble pulling and pushing commit for level-0**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/6" expanded>

Hi, I am trying to commit my level-0 change for iP, however I am receiving the following problems when pushing and pulling. Does anyone know what I can do in this situation? I Googled but don't quite know how to apply the solutions online.

Pull:
```
git -c diff.mnemonicprefix=false -c core.quotepath=false --no-optional-locks fetch --no-tags origin

git -c diff.mnemonicprefix=false -c core.quotepath=false --no-optional-locks pull origin master
From https://github.com/choongzhanhong/ip
 * branch            master     -&gt; FETCH_HEAD

hint: You have divergent branches and need to specify how to reconcile them.
hint: You can do so by running one of the following commands sometime before
hint: your next pull:
hint: 
hint:   git config pull.rebase false  # merge
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
fatal: Need to specify how to reconcile divergent branches.
```

and
Push error message: 

```
git -c diff.mnemonicprefix=false -c core.quotepath=false --no-optional-locks push -v --tags origin master:master
Pushing to https://github.com/choongzhanhong/ip.git
To https://github.com/choongzhanhong/ip.git
 ! [rejected]        master -&gt; master (non-fast-forward)
error: failed to push some refs to 'https://github.com/choongzhanhong/ip.git'


hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.



Completed with errors, see above.
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/6#issuecomment-1383133469" expanded>

running `git log` I have a log of a commit I made:
```
$ git log
commit 1ee7646a757d98ec4302d3d39b000e64d849d87b (HEAD -&gt; master)
Author: choongzhanhong <choongorilla@gmail.com>
Date:   Sun Jan 15 18:37:35 2023 +0800

    .gitignore: add *.class
    Duke.java: add level-0 greet and exit message
```
before that, it is
```
commit 3b83789e9ed75b9498c05ee150c073f6492ec6ff
Author: Sean Leong <70213029+seanleong339@users.noreply.github.com>
Date:   Thu Dec 29 13:56:26 2022 +0800

    .gitignore: Fix ACTUAL.txt -&gt; ACTUAL.TXT  (#73)
```
and so on.

`git status` shows:
```
$ git status
On branch master
Your branch and 'origin/master' have diverged,
and have 1 and 1 different commits each, respectively.
  (use "git pull" to merge the remote branch into yours)

nothing to commit, working tree clean
```
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/6#issuecomment-1383157455" expanded>

Thank you! I have force pushed the commit from my local end. I'm not sure what caused the discrepancy, but for those who are using Sourcetree like me, there is a button on top-right to input **terminal** commands simply labeled terminal.
I just used `git push --force` and it was successful. 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/13#issuecomment-1407858363" expanded>

> There are no such restrictions; input can be anything.
> However, you can define the format of the command (e.g., using only / as the separator)

Can I confirm, this means we can specify input to be in the format like: `/todo taskname` so it's easier to identify an input?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/21#issuecomment-1413081043" expanded>

I used the included batch file and added the flag so line 10 looks like this: `javac  -cp ..\src\main\java -encoding ISO-8859-1 -Xlint:none -d ..\bin ..\src\main\java\*.java`

I got the output in ACTUAL.txt. Changed nothing else. If I run it in IntelliJ, I get to see my desired logo (Like in your output). However, running it in cmd or redirecting to another file leads to the weird glyphs.

I tried changing the encoding in the code itself, such as with `PrintStream out = new PrintStream(System.out, true, "UTF-8");`
Didn't work, but I didnt spend much time digging into the issue as of now.

I think I can just change the logo to feature characters that are more available on all platforms, it's purely cosmetic.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/21#issuecomment-1418403339" expanded>

On IntelliJ Terminal:
```
"C:\Program Files\Java\jdk-19\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.1\lib\idea_rt.jar=63575:C:\Program Files\JetBrains\IntelliJ IDEA 2022.3.1\bin" -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8 -classpath D:\Documents\CS2113Projects\iP\out\production\iP Duke
██████╗  █████╗ ██████╗  █████╗ 
██╔══██╗██╔══██╗██╔══██╗██╔══██╗
██████╔╝███████║██████╔╝███████║
██╔═══╝ ██╔══██║██╔═══╝ ██╔══██║
██║     ██║  ██║██║     ██║  ██║
╚═╝     ╚═╝  ╚═╝╚═╝     ╚═╝  ╚═╝
================================
Hello! I'm PAPA, your Personal Assistant, Personal Angel.
What can I do for you? Type 'help' for a list of commands.
================================
>
```

in cmd (Windows)

``` D:\Documents\CS2113Projects\iP\bin>java Duke
???????  ?????? ???????  ??????
????????????????????????????????
????????????????????????????????
??????? ??????????????? ????????
???     ???  ??????     ???  ???
???     ???  ??????     ???  ???
================================
Hello! I'm PAPA, your Personal Assistant, Personal Angel.
What can I do for you? Type 'help' for a list of commands.
================================
>
```

Looking at the IntelliJ output, seems like there is some automatic encoding on my end such that it works in the IntelliJ Console. 
</panel>

</panel>


<panel type="info" header="### 4. PERE..AMES `@Magmanat` (8 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request to use PC Part Picker data from web scraping**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/44" expanded>

## Library

PC Part Picker website unofficial API

## Purpose

Scrape data for our pc parts tp application


https://github.com/JonathanVusich/pcpartpicker



</panel>

<panel  header="**2. :fas-info-circle: failed to push tag A-JavaDoc**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/31" expanded>

tried to tag and push A-JavaDoc

Commands that were used:
```
git tag -a "A-JavaDoc"
git push origin "A-JavaDoc" 
```

Error that comes out:
```
error: src refspec A-JavaDoc matches more than one
error: failed to push some refs to 'https://github.com/Magmanat/ip.git'
```


anyone faced this and knows how to solve this issue?

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/5#issuecomment-1385022766" expanded>

I tested the code with my own IDE, i printed true/false string into the terminal, got 1.0/1.0 AC for Question 2
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/18#issuecomment-1407621966" expanded>

This is because in your first version, since your array starts off as size 100, and you are keeping track of the size of instantiated shapes using "shapeCount". It will automatically iterate from start to end, eventually hitting a null value in that array which has no callable .area(). 

But in the second version, your for loop is limited by "shapeCount", hence it will not result in this error
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/22#issuecomment-1415393666" expanded>

Very nice!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/27#issuecomment-1426964887" expanded>

I think its just to ensure the main class you are running is cleaner.

Could always break up your exceptions into several different exception packages to further classify them and would be much easier to reference 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/31#issuecomment-1439437030" expanded>

ok i found out the issue and it was due to me accidentally naming my branch the exact same name oops
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/44#issuecomment-1484399257" expanded>

@okkhoy It is mainly to just scrape data for existing PC parts such as CPU's, GPU's along with their specifications. This data will be used in a json file which will load into the application
</panel>

</panel>


<panel type="info" header="### 5. ENG ..VIEL `@avielcx` (6 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Coursemology Week 4 Qn 3**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/16" expanded>

Hi Prof

I have the same output as the sample test case on my terminal but it stills shows wrong answer on coursemology. Appreciate your help.

</panel>

<panel  header="**2. :fas-info-circle: number of task**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/11" expanded>

Hi Prof

Do we assume that the maximum number of tasks is still 100 for level 1-3? so we can use fixed sized array?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1382688737" expanded>

i clicked finalise submission as well. How do we rectify?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/13#issuecomment-1403070708" expanded>

@okkhoy . Hi Prof, could clarify your statement above? How do we deal with inputs meant to append to the list but involve the word "mark" and "unmark"?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/13#issuecomment-1404463499" expanded>

@okkhoy what if keywords appear at the start, such as `mark papers` ?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/16#issuecomment-1407329076" expanded>

@irving11119 yea, I copied and pasted from the notes. It passed the verify test case and failed the other.
</panel>

</panel>


<panel type="info" header="### 6. NIKH..DHAR `@nikkiDEEE` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Unable to load graphviz on Mac**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/38" expanded>

Hi, i cannot find the dot.exe exectuable on Mac OS using both 

homebrew:
![image](https://user-images.githubusercontent.com/88139349/226591123-23d59f47-a7ea-4d5b-9993-50e8a92853a9.png)

and macports:
<img width="1728" alt="image" src="https://user-images.githubusercontent.com/88139349/226591085-a9a7c0e6-b42c-4e24-8a19-af3f1302aecf.png">

at first i thought if its just the dot file that needed to be loaded on intellij but that didnt seem to work. Would appreciate any help, thanks!

</panel>

<panel  header="**2. :fas-info-circle: Participation marks query**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/15" expanded>

As long as we submit the Coursemology programming exercise the midnight before the tutorial, do I get the full participation marks ? The submission before monday (end of lecture + 4 days) only applies to quizzes right? Just clarifying, thank you
</panel>

<panel  header="**3. :fas-info-circle: Confirm submission**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/14" expanded>

The requirements for uploading our iP projects are to just
    1. naming the project on our github repo "iP"
    2. updating the tags are required "Level-0, A-CodingStandard" etc 
am i missing anything?
</panel>

<panel  header="**4. :fas-info-circle: Rename origin**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/12" expanded>

Sorry if this has been mentioned before, but do we have to follow the remote name 'origin' in the `git push -u origin master` or can it be the name of our remote repo e.g. `git push -u DukeBot master`?
</panel>

<panel  header="**5. :fas-info-circle: Push level 0 to github?**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/7" expanded>

Do we have to push level 0 of our iP to Github yet? Because it says "Add increment: level 0"
</panel>

</panel>


<panel type="info" header="### 7. MITC..LVIN `@mitchmalvin1` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: text-ui-test script does not work as intended**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/19" expanded>

My ACTUAL.TXT and my EXPECTED.TXT are exactly identical and I have made sure that the spacing is also identical, however it still fails the test, I read from the tutorial page that it is because the ending line of the two files are different and that the solution is 

Solution: You can use the dos2unix utility (available in git-bash and *nix operating systems) to convert a file to Unix format.

I am not sure how I am supposed to implement this, do I change the script?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/5#issuecomment-1383083745" expanded>

Consequently, once we finalize the submission (at least for me), the grade received is only 3.0/4/0 because question 2 is 0.0/1.0. Is it meant to be that way?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/5#issuecomment-1396537519" expanded>

@okkhoy hi prof, can I resubmit for question 2 as well? In that case, will it go over the deadline?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/7#issuecomment-1398638695" expanded>

do we just need to commit together with the tag Level-0? how do we know if the script has successfully detected it?

</panel>

</panel>


<panel type="info" header="### 8. OW Y..XUAN `@jinxuan-owyong` (4 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request to use Hugo for docs**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/33" expanded>

## Library

[Hugo](https://gohugo.io/)

## Purpose

Allows various themes to be applied to the documentation page.

## License

__Hugo__

Apache 2.0
https://gohugo.io/about/license/

__Theme__ 
Varies depending on [theme](https://themes.gohugo.io/) chosen. Would like to use [Book](https://github.com/alex-shpak/hugo-book) (License: [MIT](https://github.com/alex-shpak/hugo-book/blob/master/LICENSE))

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/24#issuecomment-1418184124" expanded>

If you wish to keep the current implementation of `foo()` while avoiding `ClassCastException`, you could also consider checking whether the underlying object is what you expect using `instanceof`. 

Here's an example you can consider:

```java
public static void foo(Animal a) {
    a.speak();
    if (a instanceof Cat) {
      Cat c = (Cat) a; // downcast a to a Cat
        c.speak();
    }
    if (a instanceof DomesticCat) {
        DomesticCat dc = (DomesticCat) a; // downcast a to a DomesticCat
        dc.speak();
        dc.catchMice();
    }
}
```


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/1#issuecomment-1425311756" expanded>

The answer for the [user stories exercise (W6.7b)](https://nus-cs2113-ay2223s2.github.io/website/schedule/week6/topics.html#user-stories-repeated-from-last-week)  seems to be incorrectly displayed. 

__Expected format__
![image](https://user-images.githubusercontent.com/87897838/218029553-1e47996c-84f1-4cb5-882b-8fd019facc2e.png)

__Actual format__
![image](https://user-images.githubusercontent.com/87897838/218029030-10133517-371e-43f9-876c-865f4c5955dd.png)

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/22#issuecomment-1425369819" expanded>

The use of "the" seems to be confusing. The first half of the third sentence implies that the library is pending approval, which contradicts with the approval which has already been given. I think this would be more appropriate for phrasing the third sentence.

> Once ~the~ __a__ library is approved, it is approved for everyone in the class.
</panel>

</panel>


<panel type="info" header="### 9. YEK ..OLAS `@nichyjt` (3 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/24#issuecomment-1417417500" expanded>

I thnk that `foo()` will only work if the underlying object passed into the function is a class `DomesticCat`. 
If line 5-7 is removed, then both Cat and Domestic Cat will work.

This is because during runtime, when an object is being casted, Java will look at the underlying object (not its label, the LHS identifier) and see if the underlying object can fit into the casted class type.  

If the underlying object cannot be 'matched' to the casted class, it will throw a `ClassCastException`.
'Matching' here works only when the underlying object is a Subclass (or the class itself) of the casted class.

**For example**:
```java
// animal is labelled as an Animal, but the underlying object is a DomesticCat on heap memory
Animal animal = new DomesticCat(); 

// The downcasting works because the underlying object 
// is a Domestic Cat even though it was labelled as an Animal
DomesticCat domestic = (DomesticCat) animal; 

// This works too due to similar reasoning
Cat cat = (Cat) animal;
```

In the context of the code snippet given, this is a minimally reproducible piece of code you can try playing around with! (Tested on an online playground)
```java
class Animal{
    void speak(){
        System.out.println("I'm an animal");
    }
}

class Cat extends Animal{
    @Override
    void speak() {
        System.out.println("I'm a Cat");
    }
}

class DomesticCat extends Cat{
    @Override
    void speak() {
        System.out.println("I'm a DomesticCat");
    }
    void catchMice(){
        System.out.println("I caught a mouse!");
    }
}

public class Main {
    public static void foo(Animal a){
        a.speak();
        Cat c = (Cat)a; // downcast a to a Cat
        c.speak();
        DomesticCat dc = (DomesticCat)a; // downcast a to a DomesticCat
        dc.speak();
        dc.catchMice();
    }
    
    public static void main(String[] args) {
        Animal animal = new Animal();
        // foo(animal); // error
        Cat cat = new Cat();
        // foo(cat); // error
        
        Cat cat1 = new DomesticCat();
        foo(cat1); // OK
        System.out.println("-------------");
        Animal stillACat = (Animal) cat1;
        foo(stillACat); // OK
    }
}
```

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/34#issuecomment-1463563460" expanded>

Wen Jun brings up good ideas!

To add on, I think that in terms of design[&hat;1], static variables should only be used for properties that we know for sure will not change across the subclasses, like pre-set string messages.

[&hat;1]: Here's a good [StackOverflow post](https://stackoverflow.com/questions/21155438/when-to-use-static-variables-methods-and-when-to-use-instance-variables-methods) discussing the usage of `static`.

In this case, since `genus`, `species` and `diet` change across subclasses, `static` may not be appropriate to use here.

Based on the context given and variable naming, I'm guessing that the intent behind these variables are being set as `static final` is to:
1. Prevent accidentally changing the values
2. Have an easy way to access these unchangeable (constant) values

If that's the case, perhaps it may be better to use a `get` approach and programatically set the 'constant' values on construction? 

The idea: within Animal and its subclasses, assign `genus`, `species`, `diet` in the constructor and only expose a getter function. If you want to make it even more watertight, declare the getter functions as `final` to [prevent overriding](https://www.tutorialspoint.com/What-is-a-final-method-in-Java).
```java
class Cat extends Animal {

    // Your psuedo-constants
    private String genus;
    private String diet;
    private String species;

    public Cat(){
        super();
        this.genus = "Felis";
        this.species = "Felis catus";
        this.diet = "Fish and caviar";
    }
    
    // Only expose getter methods to the psuedo constant variables
    // use final to prevent this method from being overriden
    public final String getSpecies() {
        return this.species;
    }   
    //...
}

```

This way, although the 3 variables are not true 'constants', this implementation still meets the (1.) and (2.) requirements without needing to do much hacking around `static final` to overcome Java language restrictions!

But if there really is a need to create `static` variables, then it is technically possible to change the state if you use Container-based classes like `ArrayList` or `HashMap`.  You could store your metadata in a container of your choice and use the `.add()` `.get()` methods (or their equivalent). This is legal as the container object on heap is not being destroyed. 
I wouldn't recommend this approach though, as it may be harder to maintain in the long run.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/36#issuecomment-1465372066" expanded>

There is actually a autoformat code on save (Ctrl-S) function on Intellij:

`File > Settings > Tools > Actions on Save >  Reformat code checkbox`

Here's how the screen looks like:
![image](https://user-images.githubusercontent.com/69704055/224587673-5d3b0425-7359-4275-b1c9-70d488df59be.png)

So, on Ctrl-S the code will automatically get formatted. 

I think this is what you're looking for!

Reference from [intellij](https://www.jetbrains.com/help/idea/reformat-and-rearrange-code.html#reformat-on-save) themselves
</panel>

</panel>


<panel type="info" header="### 10. LINU..A HE `@linuspuah` (3 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: runtest .bat fails to redirect output to ACTUAL.TXT**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/20" expanded>

When i enter runtest .bat in my terminal an empty ACTUAL.TXT file is created in the text-ui-test folder. I am unsure why it is empty, the output of my program is being printed in the terminal but it is not being redirected to the ACTUAL.TXT file.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/7#issuecomment-1398300297" expanded>

if i have already pushed to github is that okay? 

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/20#issuecomment-1410005709" expanded>

Issue resolved, needed to change the name from duke to my file name in line 18 of the runtest.bat file
</panel>

</panel>


<panel type="info" header="### 11. TAN .. LIN `@T-Wan-Lin` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request to use NUSMods API**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/42" expanded>

## Library

NUSMods API - https://api.nusmods.com/v2/

## Purpose

We used it to scrape data on module information and class schedules (day and time)

## License

MIT - https://github.com/nusmodifications/nusmods/blob/master/LICENSE 

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1382652472" expanded>

Hello, I am having the same problem and I think it might be because I clicked "Finalise Submission" thinking it was finalising the submission per question attempted but it finalised the submission for all the questions, attempted or not. 

If that's the case, is it possible for the admin side to void my submission? Thank you!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1384050628" expanded>

@okkhoy Full name: Tan Wan Lin

Thank you so much and sorry for the inconvenience!


</panel>

</panel>


<panel type="info" header="### 12. TANG..XUAN `@tangphi` (3 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/16#issuecomment-1407394473" expanded>

I think I have the same problem where it is failing the Main.main(args), but passing the Main.main(args)(Verify)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/16#issuecomment-1407398138" expanded>

public class Main {
    //TODO add your methods here

    private static Shape[] shapes = new Shape[100];

    private static int shapeCount = 0;

    public static void addShape(Shape s){
        shapes[shapeCount] = s;
        shapeCount++;
    }

    public static void printAreas() {
        for (int i = 0; i &gt; shapeCount; i++) {
            System.out.println(shapes[i].area() + "\n");
        }
    }

    public static void main(String[] args) {
        addShape(new Circle(5));
        addShape(new Rectangle(3, 4));
        addShape(new Circle(10));
        printAreas();
        addShape(new Rectangle(4, 4));
        printAreas();
    }
}

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/16#issuecomment-1407399715" expanded>

Thanks deleting the \n worked!
</panel>

</panel>


<panel type="info" header="### 13. BENJ..MING `@Bawfen` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request to use retrofit for performing HTTP requests to external APIs**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/39" expanded>

## Library

[retrofit](https://github.com/square/retrofit)

## Purpose

Making HTTP requests to external APIs.

## License

Apache 2.0
https://github.com/square/retrofit/blob/master/LICENSE.txt
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/39#issuecomment-1482281906" expanded>

We are planning to use an API that returns up-to-date exchange rates, using the free tier of https://apilayer.com/marketplace/exchangerates_data-api
</panel>

</panel>


<panel type="info" header="### 14. MUTH..KHIL `@lihka1202` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: 💡Usage of static methods in Java**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/10" expanded>

While I was reading through the notes and working on the exercises, I had a clearer understanding about the usability of **static variables** in classes. However, I was trying to understand the use cases for **static methods** and I came across a pretty handy guide so I thought I'd put it here.

https://www.baeldung.com/java-static-methods-use-cases

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/9#issuecomment-1400318210" expanded>

Yep, aside from the spacing and `println` vs `print`, the other important thing is to format the final line properly. Just using `.toString` would yield `0.0` if the sum is 0, however coursemology requires the output to be `0.00`.
</panel>

</panel>


<panel type="info" header="### 15. SIUT..MENT `@clement559` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: wrong key exercise for week 2**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/4" expanded>

hello, is this the wrong key exercise for week 2? it's stated in coursemology that Q1 is bye world, but on the module website, the first key exercise is compare names. coursemology also doesn't have a question for the 2nd key exercise - grade helper.

![image](https://user-images.githubusercontent.com/84951396/212458080-59ef9f33-efac-4897-9348-b7945b98abef.png)

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/4#issuecomment-1383342983" expanded>

> Question 1 seems to be bye world to me, not sure if you are accessing the correct module website
> 
> ![image](https://user-images.githubusercontent.com/60569243/212580357-dc07b314-fef4-4a3b-a8e3-a0d12798cb78.png)

referring back to the module website, bye world is not one of the key exercises for week 2, instead grade helper should be in coursemology but isn't
![image](https://user-images.githubusercontent.com/84951396/212581255-f8a9c5c5-f644-473c-9277-e90aa8d72b76.png)

</panel>

</panel>


<panel type="info" header="### 16. BRAN.. WEI `@brennanzuz` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Preferred method to implement data?**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/34" expanded>

Say I have a parent class named `Animal`. Animal has a bunch of static attributes (variables) like `genus`, `species`, `diet`, that are currently set to nothing. Now I create a `Chicken` child class that extends `Animal`, and I want to use these static variables and set them to a fixed and final value like `gallus`, `gallus gallus` and `worms and seeds`.

I've read that it's impossible to override static variables (https://stackoverflow.com/questions/19457114/java-overriding-static-variable-of-parent-class), and that such a behavior can be remedied with a database, but since we cannot implement a database for our team project, what should we do?
</panel>

<panel  header="**2. :fas-info-circle: For each loop causes error**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/18" expanded>

With reference to Coursemology Week 4 Q3, if one uses the for each loop for `printAreas()` like this:
```
    private static void printAreas() {
        for (Shape shape : shapes) {
            System.out.println(shape.area());
        }
    }
```
This error will show: `Exception in thread "main" java.lang.NullPointerException: Cannot invoke "week_4.Q3.Shape.area()" because "shape" is null`
Whereas if you used the normal for loop:
```
   private static void printAreas() {
        for (int i = 0; i < shapeCount; i += 1) {
            System.out.println(shapes[i].area());
        }
    }
```
It works. Why makes this for each loop different from the for loop?
</panel>

</panel>


<panel type="info" header="### 17. KOH ..RCUS `@Koh-Jing-Jie-Marcus` (2 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1383691582" expanded>

Full name: Koh Jing Jie Marcus
thanks prof
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1396309828" expanded>

Full name: Koh Jing Jie Marcus
Thanks prof
</panel>

</panel>


<panel type="info" header="### 18. GOH ..ARON `@GohJW` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request to use MAS currency exchange rate API**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/46" expanded>

## Library

[API for Exchange Rates - End of Period, Daily](https://secure.mas.gov.sg/api/APIDescPage.aspx?resource_id=95932927-c8bc-4e7a-b484-68a66a24edfe)

## Purpose

Retrieval of exchange rates for the particular day.

## License

[Open Data Licence](https://www.mas.gov.sg/terms-of-use/open-data-licence)

</panel>

<panel  header="**2. :fas-info-circle: Request to use threeten-extra for retrieving previous working calander day.**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/41" expanded>

## Library

[threeten-extra](https://www.threeten.org/threeten-extra/)

## Purpose

Additional temporal for LocalDate class to find previous working calander day.

## License

BSD 3-Clause
https://www.threeten.org/threeten-extra/licenses.html
</panel>

</panel>


<panel type="info" header="### 19. ANG ..RREN `@darrenangwx` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Regarding downcasting code in W5.1**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/24" expanded>

Regarding ```Cat c = (Cat)a``` in ```foo``` method, does it only work if ```a``` is set as ```Animal a = new DomesticCat();``` or ```Animal a = new Cat();``` ? 
![image](https://user-images.githubusercontent.com/15652564/216757109-eefecb3b-b045-45c2-94cc-6e5ea52b8b81.png)

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1383116759" expanded>

> Hello, I am having the same problem and I think it might be because I clicked "Finalise Submission" thinking it was finalising the submission per question attempted but it finalised the submission for all the questions, attempted or not.
> 
> If that's the case, is it possible for the admin side to void my submission? Thank you!

I did this as well. I thought it was submission for question 1. but it submitted the whole 1 to 4.
</panel>

</panel>


<panel type="info" header="### 20. CHUA..JUIN `@wanjuin` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Finding out who is my groupmate?**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/17" expanded>

Hi, may I ask how to check who is my groupmates as I am absent from tutorial last week. Thank you!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/17#issuecomment-1407859422" expanded>

Thank you!
</panel>

</panel>


<panel type="info" header="### 21. WANG..LANG `@JangusRoundstone` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Public Class Exception vs Public Static Nested Class Exception**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/27" expanded>

<img width="681" alt="Screen Shot 2023-02-08 at 11 39 49 PM" src="https://user-images.githubusercontent.com/88696064/217577466-414fdbcf-74c4-44bc-bcfe-1e6f770e3300.png">

In the 3rd key exercise in week 5, IllegalShapeException given is defined without the static keyword. From what I found the convention is indeed to define exception as a public class, and not as a static nested class inside the main class. 

May I know why that is the case? Are there uses to exceptions defined as static nested class inside main? Based on my understanding, static nested exception class could potentially be useful for defining very specific exception that is exclusive to current main class you are running.

Any thoughts are welcomed!
</panel>

<panel  header="**2. :fas-info-circle: Possible typo in Week 5 lecture UML example**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/26" expanded>

<img width="695" alt="Screen Shot 2023-02-08 at 10 01 18 PM" src="https://user-images.githubusercontent.com/88696064/217551159-a145e236-d3de-45cb-bb3e-9678dfcce38c.png">

Just wanting to confirm, in the context of UML and interface, instead of "dashed lines indicate interface inheritance", I believe what the example is trying to say is "dashed lines indicate interface implementation"?
</panel>

</panel>


<panel type="info" header="### 22. BAEK..GYUN `@L0Z1K` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: There is no test case for Question 2 in Week 2 on Coursemology.**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/5" expanded>

<img width="1200" alt="image" src="https://user-images.githubusercontent.com/64528476/212459747-ba4f02eb-8c96-48a5-bb10-c996cd73e01f.png">

There is no test case for Question 2, until other questions have a test case. Is this intentional?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1382660739" expanded>

~Did you get invitation link of Coursemology? I didn't receive that email now. :(~
It was in my spam..
</panel>

</panel>


<panel type="info" header="### 23. ZHAN..ANXU `@danxuZhang` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Didnt Receive Invitation for Coursemology**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/3" expanded>

On the Course Website, it wrote:

> You'll receive the invitation to Coursemology sometime close to the first lecture.  

But I haven't received an invitation yet. Would you be able to send me the invitation again? Thanks. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/3#issuecomment-1382640656" expanded>

I also found it in my spam folder lol. Thank you!
</panel>

</panel>


<panel type="info" header="### 24. THIO..KIAT `@Thiolk` (2 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1383110931" expanded>

I encounter the same problem as well where i finalise my submission after the first question
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1383641123" expanded>

@okkhoy my full name is Thio Leng Kiat, thank you
</panel>

</panel>


<panel type="info" header="### 25. FOO ..ROME `@jeromeongithub` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Input for duke level-3**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/13" expanded>

Can we assume that there won't be tasks like "mark papers" which start with "mark"/"unmark"?
</panel>

</panel>


<panel type="info" header="### 26. EUGE..HING `@EangJS` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1383158974" expanded>

I did this as well. I thought it was submission for question 1. but it submitted from 1 to 4.
</panel>

</panel>


<panel type="info" header="### 27. LIM .. YAO `@LimHongYao` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1384369398" expanded>

@okkhoy full name: Lim Hong Yao
sorry about the trouble and thanks!
</panel>

</panel>


<panel type="info" header="### 28. TAN ..RETH `@Geeeetyx` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1398055789" expanded>

@okkhoy Full name: Tan Yu Xiang, Gareth

Thank you prof
</panel>

</panel>


<panel type="info" header="### 29. EU Z..G XI `@euzhengxi` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Text-ui-test**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/45" expanded>

Hi Prof and all, 

My group's TP requires input to be given line by line but the text-ui-test seems providing all inputs in one go into the program. This has resulted in the failure of the text-ui-test. Is anyone else facing this issue? Are there any workarounds for this? Thanks in advance!


Eg: 
program --> "Adding a Student ID    : new o/StudentID [NAME] /f [FOLDER_NAME]"
user --> "new o/A1234567 USR1 /f USR1"
program --> "Please enter the url: "
user --> "google.com"


program --> "Adding a Student ID    : new o/StudentID [NAME] /f [FOLDER_NAME]"
text-ui-test --> "new o/A1234567 USR1 /f USR1 google.com"
program --> "Please enter the url: "
text-ui-test -->

test failed
</panel>

</panel>


<panel type="info" header="### 30. ARIF..ALID `@Arif-Khalid` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Popup for team-based task in week 12 project tab**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/50" expanded>

In the **Week 12 Project tab**, the team-based task popup that should show up when you click on the **team-based tasks** does not work.
This same popup, however, works in Week 13 Project tab.

![image](https://user-images.githubusercontent.com/88131400/231655886-9e3a88fb-7c2c-4472-887b-fbfe3c27a801.png)

![image](https://user-images.githubusercontent.com/88131400/231655867-0a1f8905-3f7e-417d-84e2-6a61a8532a6a.png)

</panel>

</panel>


<panel type="info" header="### 31. AUNG..AING `@Aung-Phone-Naing` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Debugging help for NoSuchElementException Error**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/35" expanded>

Hi, I am using IntelliJ IDEA 2022.3.1 , Java 11 on a windows computer. So my issue is when I run the runtest.bat file for my code providing more than 1 commands in the input text file, the program starts to throw the exception NoSuchElementException in my Duke class in the run method (which basically contains the loop to take in the next line by reader until the termination command is given). The link to my repo has been attached below. @okkhoy May I seek your advise on this?

https://github.com/Aung-Phone-Naing/tp/tree/Bug-text-ui-testing-NoSuchElementException
</panel>

</panel>


<panel type="info" header="### 32. WANG..YANG `@haoyangw` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: 💡Useful git commands**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/47" expanded>

Beyond the usual git commands, here's a compilation of some I found useful during my group's TP:

-`git rebase -i HEAD~<how-many-commits>`:  Allows you to edit commits up to <how-many-commits> before the latest commit of your current branch. Change the first word before any commits(see highlighted words in screenshot below) from `pick` to `edit` to modify one or more commits' changes. Example screen of `git rebase -i`:

<img width="85" alt="image" src="https://user-images.githubusercontent.com/9844161/230269945-cd08ce51-9a60-4505-abb9-8f5ce97a5282.png">

-`git diff` and `git patch`: If you have changes to transfer to another branch conveniently, do a `git diff > changes.patch` to generate uncommitted and unstaged changes, or `git diff <another-branch> > changes.patch` to generate all changes between current and <another-branch>. Then apply the changes in another branch using `git patch changes.patch`, assuming `changes.patch` is the output file from `git diff` earlier

-`git reset --soft HEAD~<how-many-commits>`: Uncommits the past `<how-many-commits>` commits but preserves all the changes as staged files in the current branch. You can then unstage changes/add changes and `git commit` again so that you can split up the changes into different commits, make additional changes, or anything else that may be useful

`git revert <commit-SHA>`: Undos the changes made in a specific commit(identified by the commit hash). This generates a new commit that is the opposite of the specified commit(undo changes), which can be helpful when you've already pushed changes to the remote repo and don't want to force-push to modify the commit history(which is not recommended).
</panel>

</panel>


<panel type="info" header="### 33. CALE..A LE `@calebcjl` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1383644936" expanded>

@okkhoy Full name: Caleb Chan Jia Le
Thank you Prof
</panel>

</panel>


<panel type="info" header="### 34. WILS.. WEI `@WilsonLee2000` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/15#issuecomment-1406109197" expanded>

Hi professor, 
1) the quizzes will be conducted on CANVAS?
2) For the coursemology programming exercises bonus marks, aren't they counted towards participation marks as well? (for the current exercise: we need to submit early by 30 January 2359 to get that bonus mark.) But 30 January 2359 is not the midnight before my tutorial hence I'm confused.
</panel>

</panel>


<panel type="info" header="### 35. CHUA.. WEI `@pinyoko573` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: 💎Good package practices**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/29" expanded>

Was looking on how to organise my Task, Deadline, Event code and class files neatly and I found this article on two different methods of packaging. Hope this helps for people who are thinking how to name the packages!

http://www.javapractices.com/topic/TopicAction.do?Id=205

You can also look on other Github projects too
e.g. https://github.com/redhat-developer/intellij-common-ui-test-library/tree/main/src/main/java/com/redhat/devtools/intellij/commonuitest
</panel>

</panel>


<panel type="info" header="### 36. SURE.. RAM `@TopGun2001` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Help with testing out Jar file**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/32" expanded>

Hey guys, can some of y'all help me in testing my JAR file v2.0 on your systems?
Thanks!  
Link: https://github.com/TopGun2001/ip/releases/download/A-Release/CS2113_ip.jar

</panel>

</panel>


<panel type="info" header="### 37. LEO ..RREN `@dsicol` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request to use Java Money and Currency API (JSR 354)**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/43" expanded>

## Library

[Java Money and the Currency API](https://www.baeldung.com/java-money-and-currency)

## Purpose

Its purpose is to provide fast and reliable currency conversions to give our target users a good idea of their expenditure after conversion. This API does not draw from live currency updates as they have many limitations to our program.

## License

[MIT](https://github.com/eugenp/tutorials/blob/master/LICENSE)

</panel>

</panel>


<panel type="info" header="### 38. DYLA.. JIE `@ChubbsBunns` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/4#issuecomment-1383335319" expanded>

Question 1 seems to be bye world to me, not sure if you are accessing the correct module website

![image](https://user-images.githubusercontent.com/60569243/212580357-dc07b314-fef4-4a3b-a8e3-a0d12798cb78.png)

</panel>

</panel>


<panel type="info" header="### 39. SONG..IJIN `@SongZijin` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: How to get a Personal Access Token to use as password for Sourcetree💡**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/8" expanded>

I faced some trouble when trying to push my commits, I got some help from Prof and hope this can help more people. 

When setting up the account, use [Auth Type: Basic] and your GitHub username.
For the password, instead of using your GitHub password, you would need to create a Personal Access Token on GitHub, through the following steps:
1. Go to settings in GitHub
2. Scroll all the way down to [Developer Settings] on the left sidebar
3. Select [Personal Access Tokens], then [Tokens (classic)]
4. Select [Generate new token (classic)] under [Generate new token]  
5. Tick the appropriate fields as the PDF attached
6. Remember to change the expiry time to after the semester and name the token
7. After clicking [Generate token], you will see a String with a prompt to copy it, you can use that as the password for your account
Be sure to save this String and not show it to anyone else!
After setting up this account, the push of commits should work as desired.
[New Personal Access Token (Classic).pdf](https://github.com/nus-cs2113-AY2223S2/forum/files/10467050/New.Personal.Access.Token.Classic.pdf)

</panel>

</panel>


<panel type="info" header="### 40. IRVI..BOER `@irving11119` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/16#issuecomment-1407328019" expanded>

Did you update the Circle and Rectangle classes? The code for the two classes in coursemology are not by default the code provided for them in the question.
</panel>

</panel>


<panel type="info" header="### 41. OH Y..LSON `@WilsonOh` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request to use Gson library for JSON processing**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/22" expanded>

## Library

[Gson](https://github.com/google/gson)

## Purpose

JSON serialization/deserialization for iP increment Level-7. 

## License

Apache License 2.0
https://github.com/google/gson/blob/master/LICENSE

</panel>

</panel>


<panel type="info" header="### 42. JU C.. CAN `@Ju-Can` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1384144338" expanded>

@okkhoy full name: Ju Can
Thank you!
</panel>

</panel>


<panel type="info" header="### 43. LIU ..AOGE `@xiaoge26` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1383138656" expanded>

I finalised my submission as well after the first question ;-; I thought it was for question 1 only...
</panel>

</panel>


<panel type="info" header="### 44. KIM .. WON `@coregano` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/1#issuecomment-1381724639" expanded>

is this a bug?
<img width="536" alt="image" src="https://user-images.githubusercontent.com/88245041/212309815-b3f89545-6f9a-4fc3-8bc0-101db6e610df.png">
unfinished table in the last part of section W2.5c (C++ to Java → Data Types → Operators)
</panel>

</panel>


<panel type="info" header="### 45. BERN..ENDY `@BernardLesley` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1386387174" expanded>

@okkhoy full name: Bernard Lesley Efendy
I finalized my submission after the first question also. Thank you, prof!
</panel>

</panel>


<panel type="info" header="### 46. ZENG..IQIU `@ZiqiuZeng` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1396412035" expanded>

@okkhoy Full name: Zeng Ziqiu 
Thank you prof:)
</panel>

</panel>


<panel type="info" header="### 47. YANG..MING `@stephenkyang` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1396664213" expanded>

@okkhoy  Full name: Yang Stephen Ka Ming

Sorry about that, thank you professor!
</panel>

</panel>


<panel type="info" header="### 48. KALK..KAUR `@gurmankalkat` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Push branch-Level-5 & master?**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/28" expanded>

Should we push both branches to our fork or should we only push master after the merge commit?
<img width="631" alt="Screen Shot 2023-02-09 at 1 51 42 PM" src="https://user-images.githubusercontent.com/41010363/217729468-e534bcd2-7197-4ba0-a3f5-f96012fcfe55.png">

</panel>

</panel>


<panel type="info" header="### 49. NG T..KEAN `@HiIAmTzeKean` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/5#issuecomment-1385403208" expanded>

Would like to request for a resubmit for Qn 2 as the system penalised me 0/1 even though there was no test case when I submitted the code. (System marked my answer as valid)
</panel>

</panel>


<panel type="info" header="### 50. LEE ..RIEL `@azriellee` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1384224658" expanded>


@okkhoy full name: Lee Tze Weng Azriel
Thanks prof!

</panel>

</panel>


<panel type="info" header="### 51. CHEN..NZEL `@denzelcjy` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Question regarding Ctrl C exception**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/49" expanded>

Hi Prof (and everyone),

Would like to ask if the program throws an exception when the user does a Ctrl+C on the command line, is it considered a bug? 
And if it is, how severe would it be?

Example screenshot:
![image](https://user-images.githubusercontent.com/88487773/230888338-a60ca196-b92e-4ae3-91b0-85c176287f2c.png)

</panel>

</panel>


<panel type="info" header="### 52. KAEM..NGYU `@KN-CY` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request to use opencsv for writing to csv**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/37" expanded>

## Library

[opencsv](https://opencsv.sourceforge.net/)

## Purpose

Writing to csv.

## License

Apache 2.0
https://opencsv.sourceforge.net/licenses.html
</panel>

</panel>


<panel type="info" header="### 53. SAIN.. ZAW `@saintzaw` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/2#issuecomment-1385390587" expanded>

@okkhoy full name: Saint Thiri Zaw
thanks prof!
</panel>

</panel>


<panel type="info" header="### 54. ANTH.. YIP `@anthea-pr0g` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/forum/issues/5#issuecomment-1385395641" expanded>

Prof, can you help me unsubmit  Since Q2 was 0/1 for me after finalising submission as well even though it showed Green in the draft when I pressed submit. 
</panel>

</panel>
