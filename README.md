# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-22 22:23:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 91002.4 (25h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3308456
telemt_connections_bad_total 252254
telemt_connections_current 852
telemt_connections_me_current 852
telemt_handshake_timeouts_total 104893
telemt_upstream_connect_attempt_total 33473
telemt_upstream_connect_success_total 33472
telemt_upstream_connect_attempts_per_request{bucket="1"} 33472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1321
telemt_me_reconnect_success_total 550
telemt_me_reader_eof_total 565
telemt_me_idle_close_by_peer_total 565
telemt_me_route_drop_no_conn_total 2960207
telemt_me_route_drop_channel_closed_total 1227
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2777868
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 619
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 706
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 42
telemt_desync_total 11919
telemt_desync_full_logged_total 3735
telemt_desync_suppressed_total 8184
telemt_desync_frames_bucket_total{bucket="1_2"} 3223
telemt_desync_frames_bucket_total{bucket="3_10"} 4355
telemt_desync_frames_bucket_total{bucket="gt_10"} 4341
telemt_pool_swap_total 101
telemt_pool_force_close_total 3120
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 629
telemt_me_draining_writers_reap_progress_total 30593
telemt_me_writer_removed_unexpected_total 546
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2205
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28601
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3065
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27473
telemt_me_writer_teardown_success_total{mode="normal"} 30806
telemt_me_writer_teardown_noop_total 30604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61410
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.514555
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61410
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 629
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 490
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2767254
telemt_user_connections_current{user="hello"} 852
telemt_user_octets_from_client{user="hello"} 39692586088 (36.97 GB)
telemt_user_octets_to_client{user="hello"} 748801129692 (697.38 GB)
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 104368.1 (28h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3940173
telemt_connections_bad_total 356078
telemt_connections_current 918
telemt_connections_me_current 918
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99664
telemt_upstream_connect_attempt_total 62927
telemt_upstream_connect_success_total 62162
telemt_upstream_connect_fail_total 679
telemt_upstream_connect_attempts_per_request{bucket="1"} 62841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27653
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 679
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9301
telemt_me_reconnect_success_total 3419
telemt_me_reader_eof_total 3432
telemt_me_idle_close_by_peer_total 3432
telemt_me_route_drop_no_conn_total 3633635
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3135774
telemt_me_endpoint_quarantine_total 771
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 805
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 128
telemt_desync_total 12772
telemt_desync_full_logged_total 7155
telemt_desync_suppressed_total 5617
telemt_desync_frames_bucket_total{bucket="1_2"} 2881
telemt_desync_frames_bucket_total{bucket="3_10"} 5013
telemt_desync_frames_bucket_total{bucket="gt_10"} 4878
telemt_pool_swap_total 95
telemt_pool_force_close_total 2879
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 41722
telemt_me_writer_removed_unexpected_total 3370
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5722
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39395
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2452
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38843
telemt_me_writer_teardown_success_total{mode="normal"} 45117
telemt_me_writer_teardown_noop_total 41723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86840
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.429330
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86840
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 223
telemt_me_writer_restored_same_endpoint_total 3093
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 3146436
telemt_user_connections_current{user="hello"} 918
telemt_user_octets_from_client{user="hello"} 42503220731 (39.58 GB)
telemt_user_octets_to_client{user="hello"} 775713844162 (722.44 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 485
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 179228.1 (49h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16185566
telemt_connections_bad_total 1600611
telemt_connections_current 991
telemt_connections_me_current 991
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 395975
telemt_upstream_connect_attempt_total 79571
telemt_upstream_connect_success_total 79471
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 79488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1701
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2888
telemt_me_reconnect_success_total 1500
telemt_me_reader_eof_total 1446
telemt_me_idle_close_by_peer_total 1444
telemt_me_route_drop_no_conn_total 14027338
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12877734
telemt_me_endpoint_quarantine_total 1161
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1338
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 53211
telemt_desync_full_logged_total 16858
telemt_desync_suppressed_total 36353
telemt_desync_frames_bucket_total{bucket="1_2"} 11821
telemt_desync_frames_bucket_total{bucket="3_10"} 20723
telemt_desync_frames_bucket_total{bucket="gt_10"} 20667
telemt_pool_swap_total 194
telemt_pool_force_close_total 6464
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1043
telemt_me_draining_writers_reap_progress_total 59393
telemt_me_writer_removed_unexpected_total 1395
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5172
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54886
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5994
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52929
telemt_me_writer_teardown_success_total{mode="normal"} 60058
telemt_me_writer_teardown_noop_total 59446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119504
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 316.845748
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119504
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1043
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 1297
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 12877995
telemt_user_connections_current{user="hello"} 991
telemt_user_octets_from_client{user="hello"} 189801045101 (176.77 GB)
telemt_user_octets_to_client{user="hello"} 3458372036735 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 513
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 179229.5 (49h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11744846
telemt_connections_bad_total 1203871
telemt_connections_current 741
telemt_connections_me_current 741
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343717
telemt_upstream_connect_attempt_total 94045
telemt_upstream_connect_success_total 92735
telemt_upstream_connect_fail_total 863
telemt_upstream_connect_attempts_per_request{bucket="1"} 93598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3794
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 863
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4318
telemt_me_reconnect_success_total 1809
telemt_me_reader_eof_total 1670
telemt_me_idle_close_by_peer_total 1670
telemt_me_route_drop_no_conn_total 4541322
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8735954
telemt_me_endpoint_quarantine_total 1158
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1360
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 38583
telemt_desync_full_logged_total 12979
telemt_desync_suppressed_total 25604
telemt_desync_frames_bucket_total{bucket="1_2"} 9530
telemt_desync_frames_bucket_total{bucket="3_10"} 14832
telemt_desync_frames_bucket_total{bucket="gt_10"} 14221
telemt_pool_swap_total 191
telemt_pool_force_close_total 5833
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 57739
telemt_me_writer_removed_unexpected_total 1705
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5303
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53992
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5321
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51906
telemt_me_writer_teardown_success_total{mode="normal"} 59295
telemt_me_writer_teardown_noop_total 57764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117059
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.248466
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117059
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1541
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8673799
telemt_user_connections_current{user="hello"} 741
telemt_user_octets_from_client{user="hello"} 217084489048 (202.18 GB)
telemt_user_octets_to_client{user="hello"} 3929856074519 (3.57 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 179193.5 (49h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10954935
telemt_connections_bad_total 953288
telemt_connections_current 559
telemt_connections_me_current 559
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344916
telemt_upstream_connect_attempt_total 78102
telemt_upstream_connect_success_total 76587
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 76791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1939
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2332
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5536
telemt_me_reconnect_success_total 2286
telemt_me_reader_eof_total 2022
telemt_me_idle_close_by_peer_total 2021
telemt_me_route_drop_no_conn_total 5323236
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8291313
telemt_me_endpoint_quarantine_total 1232
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1314
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 26
telemt_desync_total 37862
telemt_desync_full_logged_total 12550
telemt_desync_suppressed_total 25312
telemt_desync_frames_bucket_total{bucket="1_2"} 9565
telemt_desync_frames_bucket_total{bucket="3_10"} 14481
telemt_desync_frames_bucket_total{bucket="gt_10"} 13816
telemt_pool_swap_total 186
telemt_pool_force_close_total 5755
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 729
telemt_me_draining_writers_reap_progress_total 58002
telemt_me_writer_removed_unexpected_total 2177
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6002
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54104
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52247
telemt_me_writer_teardown_success_total{mode="normal"} 60106
telemt_me_writer_teardown_noop_total 58073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118179
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.516793
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118179
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 729
telemt_me_refill_failed_total 172
telemt_me_writer_restored_same_endpoint_total 1980
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 8283305
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 192019056009 (178.83 GB)
telemt_user_octets_to_client{user="hello"} 3444575535081 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 49473.5 (13h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11073971
telemt_connections_bad_total 667007
telemt_connections_current 1163
telemt_connections_me_current 1163
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 251983
telemt_upstream_connect_attempt_total 51528
telemt_upstream_connect_success_total 48955
telemt_upstream_connect_fail_total 1740
telemt_upstream_connect_attempts_per_request{bucket="1"} 50695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16374
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5987
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1740
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7061
telemt_me_reconnect_success_total 1048
telemt_me_reader_eof_total 661
telemt_me_idle_close_by_peer_total 660
telemt_me_route_drop_no_conn_total 25262782
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9198441
telemt_me_endpoint_quarantine_total 339
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 389
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 15780
telemt_desync_full_logged_total 4192
telemt_desync_suppressed_total 11588
telemt_desync_frames_bucket_total{bucket="1_2"} 3016
telemt_desync_frames_bucket_total{bucket="3_10"} 6374
telemt_desync_frames_bucket_total{bucket="gt_10"} 6390
telemt_pool_swap_total 50
telemt_pool_force_close_total 1749
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 456
telemt_me_draining_writers_reap_progress_total 14584
telemt_me_writer_removed_unexpected_total 937
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2075
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13397
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1442
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12835
telemt_me_writer_teardown_success_total{mode="normal"} 15472
telemt_me_writer_teardown_noop_total 14603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30075
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.617921
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30075
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 456
telemt_me_refill_failed_total 327
telemt_me_writer_restored_same_endpoint_total 688
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 9223122
telemt_user_connections_current{user="hello"} 1163
telemt_user_octets_from_client{user="hello"} 85789173072 (79.90 GB)
telemt_user_octets_to_client{user="hello"} 567793082942 (528.80 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 472
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 179200.0 (49h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10883197
telemt_connections_bad_total 926945
telemt_connections_current 939
telemt_connections_me_current 939
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 239188
telemt_upstream_connect_attempt_total 106919
telemt_upstream_connect_success_total 105804
telemt_upstream_connect_fail_total 946
telemt_upstream_connect_attempts_per_request{bucket="1"} 106750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 946
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72645
telemt_me_reconnect_success_total 2957
telemt_me_reader_eof_total 2653
telemt_me_idle_close_by_peer_total 2651
telemt_me_route_drop_no_conn_total 5242462
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8594105
telemt_me_endpoint_quarantine_total 1177
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1341
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 48
telemt_me_writers_warm_current 33
telemt_desync_total 45839
telemt_desync_full_logged_total 15681
telemt_desync_suppressed_total 30158
telemt_desync_frames_bucket_total{bucket="1_2"} 9298
telemt_desync_frames_bucket_total{bucket="3_10"} 17542
telemt_desync_frames_bucket_total{bucket="gt_10"} 18999
telemt_pool_swap_total 182
telemt_pool_force_close_total 5437
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 61997
telemt_me_writer_removed_unexpected_total 2686
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6516
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58198
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4688
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56560
telemt_me_writer_teardown_success_total{mode="normal"} 64714
telemt_me_writer_teardown_noop_total 61998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126712
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.175644
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126712
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 4292
telemt_me_writer_restored_same_endpoint_total 2499
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 8597183
telemt_user_connections_current{user="hello"} 939
telemt_user_octets_from_client{user="hello"} 193818604185 (180.51 GB)
telemt_user_octets_to_client{user="hello"} 3282534035444 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 116036.2 (32h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11541642
telemt_connections_bad_total 460299
telemt_connections_current 691
telemt_connections_me_current 691
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4733722
telemt_upstream_connect_attempt_total 54918
telemt_upstream_connect_success_total 54512
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 54907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_reconnect_attempts_total 48687
telemt_me_reconnect_success_total 1726
telemt_me_reader_eof_total 1390
telemt_me_idle_close_by_peer_total 1389
telemt_me_route_drop_no_conn_total 4072672
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5553016
telemt_me_endpoint_quarantine_total 751
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 879
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31207
telemt_desync_full_logged_total 10637
telemt_desync_suppressed_total 20570
telemt_desync_frames_bucket_total{bucket="1_2"} 6196
telemt_desync_frames_bucket_total{bucket="3_10"} 12315
telemt_desync_frames_bucket_total{bucket="gt_10"} 12696
telemt_pool_swap_total 122
telemt_pool_force_close_total 3684
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 40946
telemt_me_writer_removed_unexpected_total 1444
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3515
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38915
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3243
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37262
telemt_me_writer_teardown_success_total{mode="normal"} 42430
telemt_me_writer_teardown_noop_total 40953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83383
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.631479
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83383
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1531
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5545643
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 118474966288 (110.34 GB)
telemt_user_octets_to_client{user="hello"} 2135100692538 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 97007.3 (26h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1456737
telemt_connections_bad_total 36378
telemt_connections_current 638
telemt_connections_me_current 638
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29009
telemt_upstream_connect_attempt_total 45379
telemt_upstream_connect_success_total 45238
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 45351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 763
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2072
telemt_me_reconnect_success_total 856
telemt_me_reader_eof_total 837
telemt_me_idle_close_by_peer_total 837
telemt_me_route_drop_no_conn_total 503068
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1292441
telemt_me_endpoint_quarantine_total 783
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 798
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 8130
telemt_desync_full_logged_total 2459
telemt_desync_suppressed_total 5671
telemt_desync_frames_bucket_total{bucket="1_2"} 2013
telemt_desync_frames_bucket_total{bucket="3_10"} 3141
telemt_desync_frames_bucket_total{bucket="gt_10"} 2976
telemt_pool_swap_total 104
telemt_pool_force_close_total 2714
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 149
telemt_me_draining_writers_reap_progress_total 38012
telemt_me_writer_removed_unexpected_total 806
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2984
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35868
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2626
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35298
telemt_me_writer_teardown_success_total{mode="normal"} 38852
telemt_me_writer_teardown_noop_total 38016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76868
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.968882
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76868
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 149
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 726
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 1288356
telemt_user_connections_current{user="hello"} 638
telemt_user_octets_from_client{user="hello"} 25278507949 (23.54 GB)
telemt_user_octets_to_client{user="hello"} 548947479739 (511.25 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 179204.6 (49h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13206267
telemt_connections_bad_total 1566186
telemt_connections_current 995
telemt_connections_me_current 995
telemt_handshake_timeouts_total 379224
telemt_upstream_connect_attempt_total 68596
telemt_upstream_connect_success_total 68258
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 68460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2674
telemt_me_reconnect_success_total 1396
telemt_me_reader_eof_total 1365
telemt_me_idle_close_by_peer_total 1365
telemt_me_route_drop_no_conn_total 4470449
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9982721
telemt_me_endpoint_quarantine_total 1229
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1343
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 41715
telemt_desync_full_logged_total 13614
telemt_desync_suppressed_total 28101
telemt_desync_frames_bucket_total{bucket="1_2"} 10024
telemt_desync_frames_bucket_total{bucket="3_10"} 15352
telemt_desync_frames_bucket_total{bucket="gt_10"} 16339
telemt_pool_swap_total 199
telemt_pool_force_close_total 5402
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 661
telemt_me_draining_writers_reap_progress_total 61858
telemt_me_writer_removed_unexpected_total 1313
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4993
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58220
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5228
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56456
telemt_me_writer_teardown_success_total{mode="normal"} 63213
telemt_me_writer_teardown_noop_total 61860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125073
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.587470
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125073
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 661
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 1222
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 9949517
telemt_user_connections_current{user="hello"} 995
telemt_user_octets_from_client{user="hello"} 194098016144 (180.77 GB)
telemt_user_octets_to_client{user="hello"} 4409762712112 (4.01 TB)
telemt_user_unique_ips_current{user="hello"} 378
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 179201.0 (49h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11500176
telemt_connections_bad_total 1311588
telemt_connections_current 690
telemt_connections_me_current 690
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 304937
telemt_upstream_connect_attempt_total 95093
telemt_upstream_connect_success_total 94244
telemt_upstream_connect_fail_total 642
telemt_upstream_connect_attempts_per_request{bucket="1"} 94886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39881
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 642
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10097
telemt_me_reconnect_success_total 2448
telemt_me_reader_eof_total 2285
telemt_me_idle_close_by_peer_total 2284
telemt_me_seq_mismatch_total 85
telemt_me_route_drop_no_conn_total 5630381
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8883937
telemt_me_endpoint_quarantine_total 1384
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1344
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 36
telemt_desync_total 41329
telemt_desync_full_logged_total 13264
telemt_desync_suppressed_total 28065
telemt_desync_frames_bucket_total{bucket="1_2"} 10605
telemt_desync_frames_bucket_total{bucket="3_10"} 15213
telemt_desync_frames_bucket_total{bucket="gt_10"} 15511
telemt_pool_swap_total 188
telemt_pool_force_close_total 5197
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 650
telemt_me_draining_writers_reap_progress_total 61613
telemt_me_writer_removed_unexpected_total 2319
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6326
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57686
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4726
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56416
telemt_me_writer_teardown_success_total{mode="normal"} 64012
telemt_me_writer_teardown_noop_total 61618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125630
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.316249
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125630
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 650
telemt_me_refill_failed_total 395
telemt_me_writer_restored_same_endpoint_total 1986
telemt_me_writer_restored_fallback_total 117
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 8889355
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 156779124829 (146.01 GB)
telemt_user_octets_to_client{user="hello"} 3460511212639 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 72
```