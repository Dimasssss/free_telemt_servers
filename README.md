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

# Server Metrics 2026-03-22 11:57:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 53482.4 (14h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1575972
telemt_connections_bad_total 74948
telemt_connections_current 1684
telemt_connections_me_current 1684
telemt_handshake_timeouts_total 71294
telemt_upstream_connect_attempt_total 20445
telemt_upstream_connect_success_total 20444
telemt_upstream_connect_attempts_per_request{bucket="1"} 20444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 754
telemt_me_reconnect_success_total 339
telemt_me_reader_eof_total 336
telemt_me_idle_close_by_peer_total 336
telemt_me_route_drop_no_conn_total 1076882
telemt_me_route_drop_channel_closed_total 466
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1331682
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 379
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 430
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 7981
telemt_desync_full_logged_total 2388
telemt_desync_suppressed_total 5593
telemt_desync_frames_bucket_total{bucket="1_2"} 2277
telemt_desync_frames_bucket_total{bucket="3_10"} 2994
telemt_desync_frames_bucket_total{bucket="gt_10"} 2710
telemt_pool_swap_total 59
telemt_pool_force_close_total 1762
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 275
telemt_me_draining_writers_reap_progress_total 18628
telemt_me_writer_removed_unexpected_total 331
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1314
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17523
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1727
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16866
telemt_me_writer_teardown_success_total{mode="normal"} 18837
telemt_me_writer_teardown_noop_total 18630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37467
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 131.510618
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37467
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 275
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 302
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1329127
telemt_user_connections_current{user="hello"} 1684
telemt_user_octets_from_client{user="hello"} 20870742808 (19.44 GB)
telemt_user_octets_to_client{user="hello"} 393845110704 (366.80 GB)
telemt_user_unique_ips_current{user="hello"} 648
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 66848.7 (18h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2539704
telemt_connections_bad_total 222414
telemt_connections_current 1200
telemt_connections_me_current 1200
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 58207
telemt_upstream_connect_attempt_total 44413
telemt_upstream_connect_success_total 43896
telemt_upstream_connect_fail_total 457
telemt_upstream_connect_attempts_per_request{bucket="1"} 44353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16947
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 457
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3403
telemt_me_reconnect_success_total 1513
telemt_me_reader_eof_total 1396
telemt_me_idle_close_by_peer_total 1396
telemt_me_route_drop_no_conn_total 2208001
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1997494
telemt_me_endpoint_quarantine_total 573
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 525
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 7889
telemt_desync_full_logged_total 4451
telemt_desync_suppressed_total 3438
telemt_desync_frames_bucket_total{bucket="1_2"} 1832
telemt_desync_frames_bucket_total{bucket="3_10"} 3072
telemt_desync_frames_bucket_total{bucket="gt_10"} 2985
telemt_pool_swap_total 67
telemt_pool_force_close_total 1890
telemt_me_writer_close_signal_drop_total 157
telemt_me_draining_writers_reap_progress_total 26653
telemt_me_writer_removed_unexpected_total 1358
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2934
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25075
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24763
telemt_me_writer_teardown_success_total{mode="normal"} 28009
telemt_me_writer_teardown_noop_total 26653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54662
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.270872
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54662
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 157
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1257
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 2009296
telemt_user_connections_current{user="hello"} 1200
telemt_user_octets_from_client{user="hello"} 25113883375 (23.39 GB)
telemt_user_octets_to_client{user="hello"} 496392249366 (462.30 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 739
telemt_user_unique_ips_recent_window{user="hello"} 749
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 141709.0 (39h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12574149
telemt_connections_bad_total 1092754
telemt_connections_current 5711
telemt_connections_me_current 5711
telemt_handshake_timeouts_total 327722
telemt_upstream_connect_attempt_total 51582
telemt_upstream_connect_success_total 51502
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 51510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27966
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 214
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2255
telemt_me_reconnect_success_total 1182
telemt_me_reader_eof_total 1152
telemt_me_idle_close_by_peer_total 1151
telemt_me_route_drop_no_conn_total 10267921
telemt_me_route_drop_channel_closed_total 111
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10047202
telemt_me_endpoint_quarantine_total 894
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1056
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_active_current 94
telemt_desync_total 41208
telemt_desync_full_logged_total 13194
telemt_desync_suppressed_total 28014
telemt_desync_frames_bucket_total{bucket="1_2"} 9281
telemt_desync_frames_bucket_total{bucket="3_10"} 16102
telemt_desync_frames_bucket_total{bucket="gt_10"} 15825
telemt_pool_swap_total 152
telemt_pool_force_close_total 5130
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 809
telemt_me_draining_writers_reap_progress_total 46972
telemt_me_writer_removed_unexpected_total 1113
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4069
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43411
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4787
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 343
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41842
telemt_me_writer_teardown_success_total{mode="normal"} 47480
telemt_me_writer_teardown_noop_total 47016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94496
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 218.669020
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94496
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 809
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 1033
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 10035985
telemt_user_connections_current{user="hello"} 5711
telemt_user_octets_from_client{user="hello"} 148900552176 (138.67 GB)
telemt_user_octets_to_client{user="hello"} 2809026350508 (2.55 TB)
telemt_user_unique_ips_current{user="hello"} 2354
telemt_user_unique_ips_recent_window{user="hello"} 842
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 141710.1 (39h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9461267
telemt_connections_bad_total 856403
telemt_connections_current 4286
telemt_connections_me_current 4286
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 286522
telemt_upstream_connect_attempt_total 78078
telemt_upstream_connect_success_total 76954
telemt_upstream_connect_fail_total 810
telemt_upstream_connect_attempts_per_request{bucket="1"} 77764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30601
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3667
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 810
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3319
telemt_me_reconnect_success_total 1346
telemt_me_reader_eof_total 1229
telemt_me_idle_close_by_peer_total 1229
telemt_me_route_drop_no_conn_total 3808370
telemt_me_route_drop_channel_closed_total 391
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7045143
telemt_me_endpoint_quarantine_total 894
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1085
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_active_current 49
telemt_desync_total 31928
telemt_desync_full_logged_total 10806
telemt_desync_suppressed_total 21122
telemt_desync_frames_bucket_total{bucket="1_2"} 7856
telemt_desync_frames_bucket_total{bucket="3_10"} 12299
telemt_desync_frames_bucket_total{bucket="gt_10"} 11773
telemt_pool_swap_total 152
telemt_pool_force_close_total 4637
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 566
telemt_me_draining_writers_reap_progress_total 45471
telemt_me_writer_removed_unexpected_total 1262
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4056
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42543
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 372
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40834
telemt_me_writer_teardown_success_total{mode="normal"} 46599
telemt_me_writer_teardown_noop_total 45479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92078
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 80.069827
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92078
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 566
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 1147
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 6985841
telemt_user_connections_current{user="hello"} 4286
telemt_user_octets_from_client{user="hello"} 181722725137 (169.24 GB)
telemt_user_octets_to_client{user="hello"} 3197777093006 (2.91 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1585
telemt_user_unique_ips_recent_window{user="hello"} 675
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 141674.3 (39h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8936718
telemt_connections_bad_total 750955
telemt_connections_current 4771
telemt_connections_me_current 4771
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 284172
telemt_upstream_connect_attempt_total 62423
telemt_upstream_connect_success_total 61695
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 61842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29152
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1413
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3792
telemt_me_reconnect_success_total 1597
telemt_me_reader_eof_total 1479
telemt_me_idle_close_by_peer_total 1479
telemt_me_route_drop_no_conn_total 3791763
telemt_me_route_drop_channel_closed_total 262
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6723632
telemt_me_endpoint_quarantine_total 972
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1036
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 31406
telemt_desync_full_logged_total 10556
telemt_desync_suppressed_total 20850
telemt_desync_frames_bucket_total{bucket="1_2"} 7829
telemt_desync_frames_bucket_total{bucket="3_10"} 12067
telemt_desync_frames_bucket_total{bucket="gt_10"} 11510
telemt_pool_swap_total 148
telemt_pool_force_close_total 4585
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 552
telemt_me_draining_writers_reap_progress_total 46268
telemt_me_writer_removed_unexpected_total 1511
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4437
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43280
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4111
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 474
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41683
telemt_me_writer_teardown_success_total{mode="normal"} 47717
telemt_me_writer_teardown_noop_total 46288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94005
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 59.649472
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94005
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 552
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1414
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 6714630
telemt_user_connections_current{user="hello"} 4771
telemt_user_octets_from_client{user="hello"} 164310121955 (153.03 GB)
telemt_user_octets_to_client{user="hello"} 2903609167727 (2.64 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1844
telemt_user_unique_ips_recent_window{user="hello"} 590
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 11954.2 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5069718
telemt_connections_bad_total 309651
telemt_connections_current 6246
telemt_connections_me_current 6246
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 80239
telemt_upstream_connect_attempt_total 23551
telemt_upstream_connect_success_total 22498
telemt_upstream_connect_fail_total 835
telemt_upstream_connect_attempts_per_request{bucket="1"} 23333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4614
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4623
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 835
telemt_me_keepalive_timeout_total 470
telemt_me_reconnect_attempts_total 2282
telemt_me_reconnect_success_total 346
telemt_me_reader_eof_total 216
telemt_me_idle_close_by_peer_total 216
telemt_me_route_drop_no_conn_total 11780681
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4242243
telemt_me_endpoint_quarantine_total 84
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 6234
telemt_desync_full_logged_total 1611
telemt_desync_suppressed_total 4623
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 2497
telemt_desync_frames_bucket_total{bucket="gt_10"} 2566
telemt_pool_swap_total 11
telemt_pool_force_close_total 473
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 192
telemt_me_draining_writers_reap_progress_total 3142
telemt_me_writer_removed_unexpected_total 305
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2838
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 335
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 138
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2669
telemt_me_writer_teardown_success_total{mode="normal"} 3403
telemt_me_writer_teardown_noop_total 3145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6548
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.709865
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6548
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 192
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 231
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 4257387
telemt_user_connections_current{user="hello"} 6246
telemt_user_octets_from_client{user="hello"} 23087368570 (21.50 GB)
telemt_user_octets_to_client{user="hello"} 124087294891 (115.57 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2311
telemt_user_unique_ips_recent_window{user="hello"} 1290
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 141681.0 (39h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8679603
telemt_connections_bad_total 743034
telemt_connections_current 5450
telemt_connections_me_current 5450
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 182688
telemt_upstream_connect_attempt_total 87552
telemt_upstream_connect_success_total 86683
telemt_upstream_connect_fail_total 748
telemt_upstream_connect_attempts_per_request{bucket="1"} 87431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 748
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70760
telemt_me_reconnect_success_total 2259
telemt_me_reader_eof_total 1990
telemt_me_idle_close_by_peer_total 1989
telemt_me_route_drop_no_conn_total 3933617
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6860702
telemt_me_endpoint_quarantine_total 945
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1063
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_me_writers_active_current 90
telemt_desync_total 35059
telemt_desync_full_logged_total 12066
telemt_desync_suppressed_total 22993
telemt_desync_frames_bucket_total{bucket="1_2"} 7172
telemt_desync_frames_bucket_total{bucket="3_10"} 13459
telemt_desync_frames_bucket_total{bucket="gt_10"} 14428
telemt_pool_swap_total 146
telemt_pool_force_close_total 4253
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 516
telemt_me_draining_writers_reap_progress_total 48487
telemt_me_writer_removed_unexpected_total 2019
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5036
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45495
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44234
telemt_me_writer_teardown_success_total{mode="normal"} 50531
telemt_me_writer_teardown_noop_total 48488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99019
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.846872
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99019
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 516
telemt_me_refill_failed_total 4235
telemt_me_writer_restored_same_endpoint_total 1882
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 6863530
telemt_user_connections_current{user="hello"} 5450
telemt_user_octets_from_client{user="hello"} 163605685043 (152.37 GB)
telemt_user_octets_to_client{user="hello"} 2677811531881 (2.44 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2223
telemt_user_unique_ips_recent_window{user="hello"} 995
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 78517.0 (21h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8032236
telemt_connections_bad_total 289383
telemt_connections_current 3282
telemt_connections_me_current 3282
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3337702
telemt_upstream_connect_attempt_total 39966
telemt_upstream_connect_success_total 39678
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 39959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_reconnect_attempts_total 47793
telemt_me_reconnect_success_total 1348
telemt_me_reader_eof_total 1016
telemt_me_idle_close_by_peer_total 1016
telemt_me_route_drop_no_conn_total 2600800
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3930830
telemt_me_endpoint_quarantine_total 533
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 598
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 21587
telemt_desync_full_logged_total 7225
telemt_desync_suppressed_total 14362
telemt_desync_frames_bucket_total{bucket="1_2"} 4410
telemt_desync_frames_bucket_total{bucket="3_10"} 8355
telemt_desync_frames_bucket_total{bucket="gt_10"} 8822
telemt_pool_swap_total 83
telemt_pool_force_close_total 2550
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 256
telemt_me_draining_writers_reap_progress_total 27604
telemt_me_writer_removed_unexpected_total 1083
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2463
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26250
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2186
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 364
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25054
telemt_me_writer_teardown_success_total{mode="normal"} 28713
telemt_me_writer_teardown_noop_total 27611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56324
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.731997
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56324
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 256
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1200
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3928101
telemt_user_connections_current{user="hello"} 3282
telemt_user_octets_from_client{user="hello"} 90080461748 (83.89 GB)
telemt_user_octets_to_client{user="hello"} 1569496366982 (1.43 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1224
telemt_user_unique_ips_recent_window{user="hello"} 1138
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 59487.6 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 647384
telemt_connections_bad_total 6725
telemt_connections_current 963
telemt_connections_me_current 963
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 12465
telemt_upstream_connect_attempt_total 30794
telemt_upstream_connect_success_total 30720
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 30784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 1360
telemt_me_reconnect_success_total 578
telemt_me_reader_eof_total 563
telemt_me_idle_close_by_peer_total 563
telemt_me_route_drop_no_conn_total 215434
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 584133
telemt_me_endpoint_quarantine_total 538
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 498
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_me_writers_active_current 48
telemt_me_writers_warm_current 35
telemt_desync_total 3242
telemt_desync_full_logged_total 939
telemt_desync_suppressed_total 2303
telemt_desync_frames_bucket_total{bucket="1_2"} 829
telemt_desync_frames_bucket_total{bucket="3_10"} 1277
telemt_desync_frames_bucket_total{bucket="gt_10"} 1136
telemt_pool_swap_total 62
telemt_pool_force_close_total 1517
telemt_me_writer_close_signal_drop_total 80
telemt_me_draining_writers_reap_progress_total 25102
telemt_me_writer_removed_unexpected_total 545
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1885
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23781
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1441
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23585
telemt_me_writer_teardown_success_total{mode="normal"} 25666
telemt_me_writer_teardown_noop_total 25102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50768
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.705912
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50768
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 80
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 506
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 585999
telemt_user_connections_current{user="hello"} 963
telemt_user_octets_from_client{user="hello"} 11019016833 (10.26 GB)
telemt_user_octets_to_client{user="hello"} 275126881683 (256.23 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 141685.2 (39h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10515987
telemt_connections_bad_total 1232483
telemt_connections_current 4921
telemt_connections_me_current 4921
telemt_handshake_timeouts_total 279716
telemt_upstream_connect_attempt_total 54020
telemt_upstream_connect_success_total 53811
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 53972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27210
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_reconnect_attempts_total 2115
telemt_me_reconnect_success_total 1128
telemt_me_reader_eof_total 1090
telemt_me_idle_close_by_peer_total 1090
telemt_me_route_drop_no_conn_total 3079680
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 31
telemt_me_route_drop_queue_full_profile_total{profile="high"} 31
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7861248
telemt_me_endpoint_quarantine_total 986
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1067
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_active_current 50
telemt_desync_total 32215
telemt_desync_full_logged_total 10593
telemt_desync_suppressed_total 21622
telemt_desync_frames_bucket_total{bucket="1_2"} 7797
telemt_desync_frames_bucket_total{bucket="3_10"} 11843
telemt_desync_frames_bucket_total{bucket="gt_10"} 12575
telemt_pool_swap_total 157
telemt_pool_force_close_total 4284
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 531
telemt_me_draining_writers_reap_progress_total 48688
telemt_me_writer_removed_unexpected_total 1046
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3970
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45799
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4147
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 137
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44404
telemt_me_writer_teardown_success_total{mode="normal"} 49769
telemt_me_writer_teardown_noop_total 48690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98459
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.200029
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98459
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 531
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 985
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 7832619
telemt_user_connections_current{user="hello"} 4921
telemt_user_octets_from_client{user="hello"} 152244989140 (141.79 GB)
telemt_user_octets_to_client{user="hello"} 3625630120280 (3.30 TB)
telemt_user_unique_ips_current{user="hello"} 1783
telemt_user_unique_ips_recent_window{user="hello"} 702
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 141682.3 (39h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9206714
telemt_connections_bad_total 1046069
telemt_connections_current 5193
telemt_connections_me_current 5193
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 238165
telemt_upstream_connect_attempt_total 78614
telemt_upstream_connect_success_total 78047
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 78543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1973
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_reconnect_attempts_total 6703
telemt_me_reconnect_success_total 1634
telemt_me_reader_eof_total 1455
telemt_me_idle_close_by_peer_total 1455
telemt_me_seq_mismatch_total 68
telemt_me_route_drop_no_conn_total 3597887
telemt_me_route_drop_channel_closed_total 285
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7055772
telemt_me_endpoint_quarantine_total 1095
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1075
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 90
telemt_desync_total 31454
telemt_desync_full_logged_total 10308
telemt_desync_suppressed_total 21146
telemt_desync_frames_bucket_total{bucket="1_2"} 7755
telemt_desync_frames_bucket_total{bucket="3_10"} 11683
telemt_desync_frames_bucket_total{bucket="gt_10"} 12016
telemt_pool_swap_total 153
telemt_pool_force_close_total 4179
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 521
telemt_me_draining_writers_reap_progress_total 47361
telemt_me_writer_removed_unexpected_total 1475
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4650
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44251
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43182
telemt_me_writer_teardown_success_total{mode="normal"} 48901
telemt_me_writer_teardown_noop_total 47365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96266
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.109160
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96266
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 521
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1283
telemt_me_writer_restored_fallback_total 92
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 7063574
telemt_user_connections_current{user="hello"} 5192
telemt_user_octets_from_client{user="hello"} 126363632317 (117.69 GB)
telemt_user_octets_to_client{user="hello"} 2885681898351 (2.62 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2099
telemt_user_unique_ips_recent_window{user="hello"} 616
```