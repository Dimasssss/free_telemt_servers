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

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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
- Оплачен до: 25 марта
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
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
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

# Server Metrics 2026-03-21 06:33:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 35830.0 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 754358
telemt_connections_bad_total 41816
telemt_connections_current 1346
telemt_connections_me_current 1346
telemt_handshake_timeouts_total 37898
telemt_upstream_connect_attempt_total 14538
telemt_upstream_connect_success_total 14472
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 14515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 456
telemt_me_reconnect_success_total 235
telemt_me_reader_eof_total 247
telemt_me_idle_close_by_peer_total 247
telemt_me_route_drop_no_conn_total 251931
telemt_me_route_drop_channel_closed_total 59
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 565334
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_endpoint_quarantine_total 251
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 296
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 2478
telemt_desync_full_logged_total 891
telemt_desync_suppressed_total 1587
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 985
telemt_desync_frames_bucket_total{bucket="gt_10"} 977
telemt_pool_swap_total 39
telemt_pool_force_close_total 1064
telemt_me_writer_close_signal_drop_total 93
telemt_me_draining_writers_reap_progress_total 13103
telemt_me_writer_removed_unexpected_total 232
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 967
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12328
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12039
telemt_me_writer_teardown_success_total{mode="normal"} 13295
telemt_me_writer_teardown_noop_total 13104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26399
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 37.241325
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26399
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 93
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 212
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 564626
telemt_user_connections_current{user="hello"} 1346
telemt_user_octets_from_client{user="hello"} 6729362888 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 178338375740 (166.09 GB)
telemt_user_unique_ips_current{user="hello"} 499
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 35830.9 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1921343
telemt_connections_bad_total 222770
telemt_connections_current 3855
telemt_connections_me_current 3855
telemt_handshake_timeouts_total 58512
telemt_upstream_connect_attempt_total 13550
telemt_upstream_connect_success_total 13494
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 13537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 714
telemt_me_reconnect_success_total 254
telemt_me_reader_eof_total 273
telemt_me_idle_close_by_peer_total 273
telemt_me_route_drop_no_conn_total 368241
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1133440
telemt_me_endpoint_quarantine_total 224
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 288
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_writers_active_current 43
telemt_desync_total 4840
telemt_desync_full_logged_total 1690
telemt_desync_suppressed_total 3150
telemt_desync_frames_bucket_total{bucket="1_2"} 990
telemt_desync_frames_bucket_total{bucket="3_10"} 1924
telemt_desync_frames_bucket_total{bucket="gt_10"} 1926
telemt_pool_swap_total 38
telemt_pool_force_close_total 1127
telemt_me_writer_close_signal_drop_total 113
telemt_me_draining_writers_reap_progress_total 12172
telemt_me_writer_removed_unexpected_total 254
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1058
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11360
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1078
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11045
telemt_me_writer_teardown_success_total{mode="normal"} 12418
telemt_me_writer_teardown_noop_total 12172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24590
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.375332
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24590
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 113
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 222
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 1130556
telemt_user_connections_current{user="hello"} 3855
telemt_user_octets_from_client{user="hello"} 15587256504 (14.52 GB)
telemt_user_octets_to_client{user="hello"} 466544916696 (434.50 GB)
telemt_user_unique_ips_current{user="hello"} 1418
telemt_user_unique_ips_recent_window{user="hello"} 486
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 35827.4 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1259948
telemt_connections_bad_total 157884
telemt_connections_current 3424
telemt_connections_me_current 3424
telemt_handshake_timeouts_total 58544
telemt_upstream_connect_attempt_total 14642
telemt_upstream_connect_success_total 14633
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 409
telemt_me_reconnect_success_total 238
telemt_me_reader_eof_total 248
telemt_me_idle_close_by_peer_total 248
telemt_me_route_drop_no_conn_total 299742
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 971443
telemt_me_endpoint_quarantine_total 255
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 286
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
telemt_desync_total 3919
telemt_desync_full_logged_total 1426
telemt_desync_suppressed_total 2493
telemt_desync_frames_bucket_total{bucket="1_2"} 869
telemt_desync_frames_bucket_total{bucket="3_10"} 1528
telemt_desync_frames_bucket_total{bucket="gt_10"} 1522
telemt_pool_swap_total 39
telemt_pool_force_close_total 1050
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 118
telemt_me_draining_writers_reap_progress_total 13319
telemt_me_writer_removed_unexpected_total 229
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1033
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12466
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1046
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12269
telemt_me_writer_teardown_success_total{mode="normal"} 13499
telemt_me_writer_teardown_noop_total 13322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26821
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.739113
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26821
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 118
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 204
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 969365
telemt_user_connections_current{user="hello"} 3424
telemt_user_octets_from_client{user="hello"} 13470585532 (12.55 GB)
telemt_user_octets_to_client{user="hello"} 429649018312 (400.14 GB)
telemt_user_unique_ips_current{user="hello"} 1272
telemt_user_unique_ips_recent_window{user="hello"} 451
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 35828.8 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1094218
telemt_connections_bad_total 147993
telemt_connections_current 2627
telemt_connections_me_current 2627
telemt_handshake_timeouts_total 54712
telemt_upstream_connect_attempt_total 14776
telemt_upstream_connect_success_total 14688
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 14728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 649
telemt_me_reconnect_success_total 264
telemt_me_reader_eof_total 264
telemt_me_idle_close_by_peer_total 264
telemt_me_route_drop_no_conn_total 234363
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 736801
telemt_me_endpoint_quarantine_total 252
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 291
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 3242
telemt_desync_full_logged_total 1213
telemt_desync_suppressed_total 2029
telemt_desync_frames_bucket_total{bucket="1_2"} 697
telemt_desync_frames_bucket_total{bucket="3_10"} 1402
telemt_desync_frames_bucket_total{bucket="gt_10"} 1143
telemt_pool_swap_total 39
telemt_pool_force_close_total 1010
telemt_me_writer_close_signal_drop_total 50
telemt_me_draining_writers_reap_progress_total 13254
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 955
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12565
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 992
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12244
telemt_me_writer_teardown_success_total{mode="normal"} 13520
telemt_me_writer_teardown_noop_total 13255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26775
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.145511
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26775
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 50
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 225
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 735519
telemt_user_connections_current{user="hello"} 2627
telemt_user_octets_from_client{user="hello"} 13519118504 (12.59 GB)
telemt_user_octets_to_client{user="hello"} 357072724036 (332.55 GB)
telemt_user_unique_ips_current{user="hello"} 1000
telemt_user_unique_ips_recent_window{user="hello"} 353
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 35792.5 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1040438
telemt_connections_bad_total 133197
telemt_connections_current 2282
telemt_connections_me_current 2282
telemt_handshake_timeouts_total 38442
telemt_upstream_connect_attempt_total 15247
telemt_upstream_connect_success_total 15238
telemt_upstream_connect_attempts_per_request{bucket="1"} 15238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 271
telemt_me_reconnect_success_total 227
telemt_me_reader_eof_total 223
telemt_me_idle_close_by_peer_total 223
telemt_me_route_drop_no_conn_total 206842
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 730693
telemt_me_endpoint_quarantine_total 294
telemt_me_single_endpoint_shadow_rotate_total 286
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
telemt_me_writers_active_current 54
telemt_desync_total 3303
telemt_desync_full_logged_total 1274
telemt_desync_suppressed_total 2029
telemt_desync_frames_bucket_total{bucket="1_2"} 783
telemt_desync_frames_bucket_total{bucket="3_10"} 1321
telemt_desync_frames_bucket_total{bucket="gt_10"} 1199
telemt_pool_swap_total 39
telemt_pool_force_close_total 963
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 58
telemt_me_draining_writers_reap_progress_total 13818
telemt_me_writer_removed_unexpected_total 205
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 908
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13134
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 958
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12855
telemt_me_writer_teardown_success_total{mode="normal"} 14042
telemt_me_writer_teardown_noop_total 13819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27861
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.439522
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27861
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 58
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 201
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 729261
telemt_user_connections_current{user="hello"} 2282
telemt_user_octets_from_client{user="hello"} 16799166936 (15.65 GB)
telemt_user_octets_to_client{user="hello"} 377824229808 (351.88 GB)
telemt_user_unique_ips_current{user="hello"} 921
telemt_user_unique_ips_recent_window{user="hello"} 321
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 35831.9 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2137171
telemt_connections_bad_total 162092
telemt_connections_current 4571
telemt_connections_me_current 4571
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 144462
telemt_upstream_connect_attempt_total 28436
telemt_upstream_connect_success_total 27057
telemt_upstream_connect_fail_total 870
telemt_upstream_connect_attempts_per_request{bucket="1"} 27927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 431
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 870
telemt_me_reconnect_attempts_total 1747
telemt_me_reconnect_success_total 556
telemt_me_reader_eof_total 373
telemt_me_idle_close_by_peer_total 372
telemt_me_route_drop_no_conn_total 1616150
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1684121
telemt_me_endpoint_quarantine_total 282
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 78
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 78
telemt_me_single_endpoint_shadow_rotate_total 289
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
telemt_desync_total 4148
telemt_desync_full_logged_total 1567
telemt_desync_suppressed_total 2581
telemt_desync_frames_bucket_total{bucket="1_2"} 935
telemt_desync_frames_bucket_total{bucket="3_10"} 1761
telemt_desync_frames_bucket_total{bucket="gt_10"} 1452
telemt_pool_swap_total 38
telemt_pool_force_close_total 1083
telemt_me_writer_close_signal_drop_total 145
telemt_me_draining_writers_reap_progress_total 12297
telemt_me_writer_removed_unexpected_total 544
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1357
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11455
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1017
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 66
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11214
telemt_me_writer_teardown_success_total{mode="normal"} 12812
telemt_me_writer_teardown_noop_total 12301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25113
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.294867
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25113
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 145
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 359
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 1695482
telemt_user_connections_current{user="hello"} 4571
telemt_user_octets_from_client{user="hello"} 31782900420 (29.60 GB)
telemt_user_octets_to_client{user="hello"} 441803970159 (411.46 GB)
telemt_user_msgs_from_client{user="hello"} 40291
telemt_user_msgs_to_client{user="hello"} 96775
telemt_user_unique_ips_current{user="hello"} 1577
telemt_user_unique_ips_recent_window{user="hello"} 829
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 35799.4 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1114435
telemt_connections_bad_total 154902
telemt_connections_current 2268
telemt_connections_me_current 2268
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 23991
telemt_upstream_connect_attempt_total 16739
telemt_upstream_connect_success_total 16594
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 16724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_reconnect_attempts_total 1316
telemt_me_reconnect_success_total 323
telemt_me_reader_eof_total 335
telemt_me_idle_close_by_peer_total 335
telemt_me_route_drop_no_conn_total 264523
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 800980
telemt_me_endpoint_quarantine_total 241
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 289
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_active_current 46
telemt_desync_total 3221
telemt_desync_full_logged_total 1226
telemt_desync_suppressed_total 1995
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 1325
telemt_desync_frames_bucket_total{bucket="gt_10"} 1290
telemt_pool_swap_total 39
telemt_pool_force_close_total 924
telemt_me_writer_close_signal_drop_total 51
telemt_me_draining_writers_reap_progress_total 13787
telemt_me_writer_removed_unexpected_total 315
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1029
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13093
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 918
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12863
telemt_me_writer_teardown_success_total{mode="normal"} 14122
telemt_me_writer_teardown_noop_total 13787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27909
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.010686
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27909
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 51
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 250
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 798640
telemt_user_connections_current{user="hello"} 2268
telemt_user_octets_from_client{user="hello"} 12898321460 (12.01 GB)
telemt_user_octets_to_client{user="hello"} 401327504754 (373.77 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 926
telemt_user_unique_ips_recent_window{user="hello"} 366
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 35793.7 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1406342
telemt_connections_bad_total 90006
telemt_connections_current 2309
telemt_connections_me_current 2309
telemt_handshake_timeouts_total 497896
telemt_upstream_connect_attempt_total 15926
telemt_upstream_connect_success_total 15899
telemt_upstream_connect_attempts_per_request{bucket="1"} 15899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 256
telemt_me_reconnect_attempts_total 316
telemt_me_reconnect_success_total 234
telemt_me_reader_eof_total 242
telemt_me_idle_close_by_peer_total 242
telemt_me_route_drop_no_conn_total 232187
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 713697
telemt_me_endpoint_quarantine_total 306
telemt_me_single_endpoint_shadow_rotate_total 293
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 3133
telemt_desync_full_logged_total 1120
telemt_desync_suppressed_total 2013
telemt_desync_frames_bucket_total{bucket="1_2"} 580
telemt_desync_frames_bucket_total{bucket="3_10"} 1279
telemt_desync_frames_bucket_total{bucket="gt_10"} 1274
telemt_pool_swap_total 39
telemt_pool_force_close_total 892
telemt_me_writer_close_signal_drop_total 52
telemt_me_draining_writers_reap_progress_total 14263
telemt_me_writer_removed_unexpected_total 227
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 837
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13669
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 884
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13371
telemt_me_writer_teardown_success_total{mode="normal"} 14506
telemt_me_writer_teardown_noop_total 14263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28769
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.513057
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28769
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 52
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 211
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 710817
telemt_user_connections_current{user="hello"} 2309
telemt_user_octets_from_client{user="hello"} 11547132868 (10.75 GB)
telemt_user_octets_to_client{user="hello"} 370409609784 (344.97 GB)
telemt_user_unique_ips_current{user="hello"} 996
telemt_user_unique_ips_recent_window{user="hello"} 350
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 33785.3 (9h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268516
telemt_connections_bad_total 11035
telemt_connections_current 502
telemt_connections_me_current 502
telemt_handshake_timeouts_total 71894
telemt_upstream_connect_attempt_total 17299
telemt_upstream_connect_success_total 17298
telemt_upstream_connect_attempts_per_request{bucket="1"} 17298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 519
telemt_me_reconnect_success_total 247
telemt_me_reader_eof_total 259
telemt_me_idle_close_by_peer_total 259
telemt_me_route_drop_no_conn_total 64497
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174502
telemt_me_endpoint_quarantine_total 329
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 294
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_me_writers_active_current 43
telemt_desync_total 1074
telemt_desync_full_logged_total 517
telemt_desync_suppressed_total 557
telemt_desync_frames_bucket_total{bucket="1_2"} 197
telemt_desync_frames_bucket_total{bucket="3_10"} 449
telemt_desync_frames_bucket_total{bucket="gt_10"} 428
telemt_pool_swap_total 37
telemt_pool_force_close_total 756
telemt_me_writer_close_signal_drop_total 46
telemt_me_draining_writers_reap_progress_total 15437
telemt_me_writer_removed_unexpected_total 243
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1062
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14619
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 756
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14681
telemt_me_writer_teardown_success_total{mode="normal"} 15681
telemt_me_writer_teardown_noop_total 15437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31118
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.975396
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31118
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 46
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 216
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 174739
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 1885801191 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 72238602185 (67.28 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 35803.7 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1141940
telemt_connections_bad_total 86157
telemt_connections_current 3046
telemt_connections_me_current 3046
telemt_handshake_timeouts_total 30312
telemt_upstream_connect_attempt_total 16384
telemt_upstream_connect_success_total 16311
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 16355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 572
telemt_me_reconnect_success_total 327
telemt_me_reader_eof_total 312
telemt_me_idle_close_by_peer_total 312
telemt_me_route_drop_no_conn_total 243048
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 883298
telemt_me_endpoint_quarantine_total 296
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 289
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_me_writers_active_current 46
telemt_desync_total 3493
telemt_desync_full_logged_total 1164
telemt_desync_suppressed_total 2329
telemt_desync_frames_bucket_total{bucket="1_2"} 938
telemt_desync_frames_bucket_total{bucket="3_10"} 1313
telemt_desync_frames_bucket_total{bucket="gt_10"} 1242
telemt_pool_swap_total 39
telemt_pool_force_close_total 905
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 69
telemt_me_draining_writers_reap_progress_total 14797
telemt_me_writer_removed_unexpected_total 313
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1027
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14090
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 905
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13892
telemt_me_writer_teardown_success_total{mode="normal"} 15117
telemt_me_writer_teardown_noop_total 14797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29914
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.611565
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29914
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 69
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 299
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 879025
telemt_user_connections_current{user="hello"} 3046
telemt_user_octets_from_client{user="hello"} 13440899852 (12.52 GB)
telemt_user_octets_to_client{user="hello"} 397998627984 (370.67 GB)
telemt_user_unique_ips_current{user="hello"} 1139
telemt_user_unique_ips_recent_window{user="hello"} 408
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 35800.5 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1087494
telemt_connections_bad_total 70359
telemt_connections_current 2813
telemt_connections_me_current 2813
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 29003
telemt_upstream_connect_attempt_total 24935
telemt_upstream_connect_success_total 24759
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 24897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_reconnect_attempts_total 2453
telemt_me_reconnect_success_total 436
telemt_me_reader_eof_total 379
telemt_me_idle_close_by_peer_total 379
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 248954
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 862030
telemt_me_endpoint_quarantine_total 363
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 288
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
telemt_me_writers_active_current 46
telemt_desync_total 3273
telemt_desync_full_logged_total 1044
telemt_desync_suppressed_total 2229
telemt_desync_frames_bucket_total{bucket="1_2"} 982
telemt_desync_frames_bucket_total{bucket="3_10"} 1197
telemt_desync_frames_bucket_total{bucket="gt_10"} 1094
telemt_pool_swap_total 39
telemt_pool_force_close_total 874
telemt_me_writer_close_signal_drop_total 75
telemt_me_draining_writers_reap_progress_total 14024
telemt_me_writer_removed_unexpected_total 391
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1216
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13221
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 856
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13150
telemt_me_writer_teardown_success_total{mode="normal"} 14437
telemt_me_writer_teardown_noop_total 14024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28461
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.344040
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28461
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 75
telemt_me_refill_failed_total 115
telemt_me_writer_restored_same_endpoint_total 322
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 866656
telemt_user_connections_current{user="hello"} 2813
telemt_user_octets_from_client{user="hello"} 10977435747 (10.22 GB)
telemt_user_octets_to_client{user="hello"} 378748754939 (352.74 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1019
telemt_user_unique_ips_recent_window{user="hello"} 363
```