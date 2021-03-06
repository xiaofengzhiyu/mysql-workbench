set(IMAGE_FILES 
    Apply.png
    Apply_16x16.png
    Close_18x18.png
    Close_16x16.png
    Discard.png
    Discard_16x16.png
    DotBlue.png
    DotDisabled.png
    DotGrey.png
    DotRed.png
    EditorCollapsed.png
    EditorExpanded.png
    firewall-header.png
    First_16x16.png
    Last_16x16.png
    MacWizardBackground.png
    MySQL-WB-about-screen.png
    Refresh_16x16.png
    Refresh_18x18.png
    Refresh_disabled_18x18.png
    arrow_down.png
    arrow_up.png
    audit_log.png
    background.png
    background_stripes_light.png
    background_top_shadow.png
    big_switcher_no.png
    big_switcher_yes.png
    busy_sidebar.png
    busy_sidebar_mac.png
    change_alert_create.png
    change_alert_drop.png
    change_alert_thin.png
    change_backward.png
    change_forward.png
    change_ignore.png
    change_nothing.png
    check.png
    collapsing_panel_bg.png
    collapsing_panel_grid_bg.png
    collapsing_panel_grid_details.png
    collapsing_panel_grid_details2.png
    collapsing_panel_grid_large_icons.png
    collapsing_panel_grid_large_icons2.png
    collapsing_panel_grid_small_icons.png
    collapsing_panel_grid_small_icons2.png
    collapsing_panel_header_bg.png
    collapsing_panel_header_bg_flat.png
    collapsing_panel_header_shadow.png
    collapsing_panel_header_tab_add.png
    collapsing_panel_header_tab_add2.png
    collapsing_panel_header_tab_del.png
    collapsing_panel_header_tab_del2.png
    collapsing_panel_header_tab_left.png
    collapsing_panel_header_tab_left_flat.png
    collapsing_panel_header_tab_middle.png
    collapsing_panel_header_tab_middle_flat.png
    collapsing_panel_header_tab_right.png
    collapsing_panel_header_tab_right_flat.png
    collapsing_panel_header_tab_separator.png
    collapsing_panel_header_tab_separator_flat.png
    collapsing_panel_minus.png
    collapsing_panel_minus_flat.png
    collapsing_panel_plus.png
    collapsing_panel_plus_flat.png
    collapsing_panel_tab_left.png
    collapsing_panel_tab_middle.png
    collapsing_panel_tab_right.png
    dialog_input.png
    edit.png
    field_overlay_blob.png
    field_overlay_null.png
    header_bar_blue.png
    header_bar_gray.png
    header_bar_orange.png
    item_overlay_add.png
    item_overlay_delete.png
    message_confirm.png
    message_edit.png
    message_error.png
    message_warning.png
    message_wb_bug.png
    message_wb_lock.png
    message_wb_wait.png
    navigator_zoom_in.png
    navigator_zoom_out.png
    note.128x128.png
    options-horizontal-separator.png
    refresh_sidebar.png
    refresh_sidebar_mac.png
    sakila.png
    search_clear.png
    search_doc_action.png
    search_icon.png
    search_sidebar.png
    section_expanded.png
    section_unexpandable.png
    section_unexpanded.png
    separator-dots.png
    separator_vertical.png
    show_eof.png
    show_whitespace.png
    small_toolbar_bg.png
    statusbar_output.png
    statusbar_separator.png
    statusbar_shell.png
    switcher_bottom_off_win8.png
    switcher_bottom_on_win8.png
    switcher_left_off_win8.png
    switcher_left_on_win8.png
    switcher_right_off_win8.png
    switcher_right_on_win8.png
    tab.diagram.16x16.png
    tab.overview.home.16x16.png
    tab.overview.physical.16x16.png
    tab.sqlquery.16x16.png
    task_checked.png
    task_checked_mac.png
    task_disabled.png
    task_disabled_mac.png
    task_error.png
    task_error_mac.png
    task_executing.png
    task_executing_mac.png
    task_unchecked.png
    task_unchecked_mac.png
    task_warning.png
    task_warning_mac.png
    tree_collapsed.png
    tree_expanded.png
    uncheck.png
    unknown.png
    wait_panel_cancel_button.png
    wb-wizard-vista-bg.png
    wb_lock.png
    zoom_in.png
    zoom_out.png
    zoom_reset.png
    editor_breakpoint_hit.xpm
    editor_breakpoint.xpm
    editor_current_pos.xpm
    editor_error.xpm
    editor_statement.xpm
    JS_Datatype_Array.png
    JS_Datatype_Bin.png
    JS_Datatype_Bool.png
    JS_Datatype_Date.png
    JS_Datatype_Null.png
    JS_Datatype_Number.png
    JS_Datatype_Object.png
    JS_Datatype_ObjectId.png
    JS_Datatype_String.png
)

if (UNIX)
    set(IMAGE_FILES ${IMAGE_FILES}
            linux/switcher_bottom_off.png
            linux/switcher_bottom_on.png
            linux/switcher_left_off.png
            linux/switcher_left_on.png
            linux/switcher_right_off.png
            linux/switcher_right_on.png
       )
elseif (APPLE)
    set(IMAGE_FILES ${IMAGE_FILES}
            switcher_bottom_off.png
            switcher_bottom_on.png
            switcher_left_off.png
            switcher_left_on.png
            switcher_right_off.png
            switcher_right_on.png
            tab_00.png
            tab_01.png
            tab_02.png
            tab_03.png
            tab_05.png
            tab_06.png
            tab_07.png
            tab_08.png
            tab_09.png
            tab_10.png
            tab_11.png
            tab_icon_db.Routine.png
            tab_icon_db.query.QueryBuffer.png
            tab_icon_db.Schema.png
            tab_icon_db.Table.png
            tab_icon_db.View.png
       )
endif ()

install(FILES ${IMAGE_FILES} DESTINATION ${WB_PACKAGE_SHARED_DIR}/images)
