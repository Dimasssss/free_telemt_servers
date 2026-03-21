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

# Server Metrics 2026-03-21 22:21:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 4496.1 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84528
telemt_connections_bad_total 6362
telemt_connections_current 734
telemt_connections_me_current 734
telemt_handshake_timeouts_total 3961
telemt_upstream_connect_attempt_total 1762
telemt_upstream_connect_success_total 1761
telemt_upstream_connect_attempts_per_request{bucket="1"} 1761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 41
telemt_me_reconnect_success_total 23
telemt_me_reader_eof_total 24
telemt_me_idle_close_by_peer_total 24
telemt_me_route_drop_no_conn_total 17820
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68179
telemt_me_endpoint_quarantine_total 25
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 47
telemt_desync_total 496
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 342
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 4
telemt_pool_force_close_total 102
telemt_me_writer_close_signal_drop_total 9
telemt_me_draining_writers_reap_progress_total 1514
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 97
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1441
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 102
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1412
telemt_me_writer_teardown_success_total{mode="normal"} 1538
telemt_me_writer_teardown_noop_total 1514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3052
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.107809
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3052
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 9
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 68125
telemt_user_connections_current{user="hello"} 734
telemt_user_octets_from_client{user="hello"} 948649272 (904.70 MB)
telemt_user_octets_to_client{user="hello"} 25358772776 (23.62 GB)
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 17862.2 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 597386
telemt_connections_bad_total 27882
telemt_connections_current 954
telemt_connections_me_current 954
telemt_handshake_timeouts_total 21580
telemt_upstream_connect_attempt_total 7245
telemt_upstream_connect_success_total 7108
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 7230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_reconnect_attempts_total 621
telemt_me_reconnect_success_total 223
telemt_me_reader_eof_total 191
telemt_me_idle_close_by_peer_total 191
telemt_me_route_drop_no_conn_total 310861
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 485486
telemt_me_endpoint_quarantine_total 145
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_active_current 42
telemt_desync_total 2163
telemt_desync_full_logged_total 1227
telemt_desync_suppressed_total 936
telemt_desync_frames_bucket_total{bucket="1_2"} 450
telemt_desync_frames_bucket_total{bucket="3_10"} 827
telemt_desync_frames_bucket_total{bucket="gt_10"} 886
telemt_pool_swap_total 19
telemt_pool_force_close_total 554
telemt_me_writer_close_signal_drop_total 43
telemt_me_draining_writers_reap_progress_total 6360
telemt_me_writer_removed_unexpected_total 180
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 555
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5983
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 547
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5806
telemt_me_writer_teardown_success_total{mode="normal"} 6538
telemt_me_writer_teardown_noop_total 6360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12898
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.092388
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12898
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 43
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 154
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 484843
telemt_user_connections_current{user="hello"} 954
telemt_user_octets_from_client{user="hello"} 8395198680 (7.82 GB)
telemt_user_octets_to_client{user="hello"} 164883530760 (153.56 GB)
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 92722.1 (25h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7231885
telemt_connections_bad_total 554605
telemt_connections_current 2733
telemt_connections_me_current 2733
telemt_handshake_timeouts_total 226777
telemt_upstream_connect_attempt_total 33318
telemt_upstream_connect_success_total 33250
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 33257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1454
telemt_me_reconnect_success_total 706
telemt_me_reader_eof_total 717
telemt_me_idle_close_by_peer_total 717
telemt_me_route_drop_no_conn_total 4458613
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5919100
telemt_me_endpoint_quarantine_total 578
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 683
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_me_writers_warm_current 1
telemt_desync_total 25004
telemt_desync_full_logged_total 8221
telemt_desync_suppressed_total 16783
telemt_desync_frames_bucket_total{bucket="1_2"} 5375
telemt_desync_frames_bucket_total{bucket="3_10"} 9797
telemt_desync_frames_bucket_total{bucket="gt_10"} 9832
telemt_pool_swap_total 99
telemt_pool_force_close_total 3345
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 553
telemt_me_draining_writers_reap_progress_total 30328
telemt_me_writer_removed_unexpected_total 689
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2598
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28012
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3106
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26983
telemt_me_writer_teardown_success_total{mode="normal"} 30610
telemt_me_writer_teardown_noop_total 30372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60982
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 149.162221
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60982
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 553
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 631
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5911898
telemt_user_connections_current{user="hello"} 2733
telemt_user_octets_from_client{user="hello"} 101590467812 (94.61 GB)
telemt_user_octets_to_client{user="hello"} 1913614459084 (1.74 TB)
telemt_user_unique_ips_current{user="hello"} 1195
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 92723.4 (25h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5929402
telemt_connections_bad_total 573195
telemt_connections_current 2071
telemt_connections_me_current 2071
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 194164
telemt_upstream_connect_attempt_total 37294
telemt_upstream_connect_success_total 36961
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 37134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17758
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1730
telemt_me_reconnect_success_total 734
telemt_me_reader_eof_total 709
telemt_me_idle_close_by_peer_total 709
telemt_me_route_drop_no_conn_total 2080389
telemt_me_route_drop_channel_closed_total 238
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4431435
telemt_me_endpoint_quarantine_total 560
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 705
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_warm_current 1
telemt_desync_total 21373
telemt_desync_full_logged_total 7148
telemt_desync_suppressed_total 14225
telemt_desync_frames_bucket_total{bucket="1_2"} 5176
telemt_desync_frames_bucket_total{bucket="3_10"} 8258
telemt_desync_frames_bucket_total{bucket="gt_10"} 7939
telemt_pool_swap_total 101
telemt_pool_force_close_total 3065
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 339
telemt_me_draining_writers_reap_progress_total 28957
telemt_me_writer_removed_unexpected_total 686
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2491
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27084
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25892
telemt_me_writer_teardown_success_total{mode="normal"} 29575
telemt_me_writer_teardown_noop_total 28963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58538
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.443114
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58538
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 339
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 632
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4398413
telemt_user_connections_current{user="hello"} 2071
telemt_user_octets_from_client{user="hello"} 136210909261 (126.86 GB)
telemt_user_octets_to_client{user="hello"} 2048111375591 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 938
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 92687.4 (25h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5855135
telemt_connections_bad_total 532043
telemt_connections_current 1757
telemt_connections_me_current 1757
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 183112
telemt_upstream_connect_attempt_total 43689
telemt_upstream_connect_success_total 43393
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 43528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19206
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1044
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1778
telemt_me_reconnect_success_total 795
telemt_me_reader_eof_total 741
telemt_me_idle_close_by_peer_total 741
telemt_me_route_drop_no_conn_total 2068583
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4383818
telemt_me_endpoint_quarantine_total 616
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 690
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 21158
telemt_desync_full_logged_total 6949
telemt_desync_suppressed_total 14209
telemt_desync_frames_bucket_total{bucket="1_2"} 5233
telemt_desync_frames_bucket_total{bucket="3_10"} 8024
telemt_desync_frames_bucket_total{bucket="gt_10"} 7901
telemt_pool_swap_total 99
telemt_pool_force_close_total 2941
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 30373
telemt_me_writer_removed_unexpected_total 710
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2575
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28513
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2726
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27432
telemt_me_writer_teardown_success_total{mode="normal"} 31088
telemt_me_writer_teardown_noop_total 30384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61472
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.844947
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61472
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 688
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 4385512
telemt_user_connections_current{user="hello"} 1757
telemt_user_octets_from_client{user="hello"} 129297838267 (120.42 GB)
telemt_user_octets_to_client{user="hello"} 2004969570067 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 861
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 92726.8 (25h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19638359
telemt_connections_bad_total 1368683
telemt_connections_current 2662
telemt_connections_me_current 2662
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 558319
telemt_upstream_connect_attempt_total 183348
telemt_upstream_connect_success_total 166029
telemt_upstream_connect_fail_total 15821
telemt_upstream_connect_attempts_per_request{bucket="1"} 181850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8857
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15821
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59728
telemt_me_reconnect_success_total 1957
telemt_me_reader_eof_total 1288
telemt_me_idle_close_by_peer_total 1287
telemt_me_route_drop_no_conn_total 39398417
telemt_me_route_drop_channel_closed_total 120
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16068725
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 672
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 717
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_me_writers_warm_current 2
telemt_desync_total 30741
telemt_desync_full_logged_total 9096
telemt_desync_suppressed_total 21645
telemt_desync_frames_bucket_total{bucket="1_2"} 6723
telemt_desync_frames_bucket_total{bucket="3_10"} 13626
telemt_desync_frames_bucket_total{bucket="gt_10"} 10392
telemt_pool_swap_total 94
telemt_pool_force_close_total 3179
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 721
telemt_me_draining_writers_reap_progress_total 28607
telemt_me_writer_removed_unexpected_total 1838
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3873
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26299
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2671
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 508
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25428
telemt_me_writer_teardown_success_total{mode="normal"} 30172
telemt_me_writer_teardown_noop_total 28633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58805
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 208.448031
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58805
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 721
telemt_me_refill_failed_total 3520
telemt_me_writer_restored_same_endpoint_total 1376
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14245
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 16193709
telemt_user_connections_current{user="hello"} 2662
telemt_user_octets_from_client{user="hello"} 169977380910 (158.30 GB)
telemt_user_octets_to_client{user="hello"} 1049619305098 (977.53 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1174
telemt_user_unique_ips_recent_window{user="hello"} 290
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 92694.3 (25h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5678588
telemt_connections_bad_total 533281
telemt_connections_current 1934
telemt_connections_me_current 1934
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 117781
telemt_upstream_connect_attempt_total 51092
telemt_upstream_connect_success_total 50563
telemt_upstream_connect_fail_total 443
telemt_upstream_connect_attempts_per_request{bucket="1"} 51006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 443
telemt_me_reconnect_attempts_total 11329
telemt_me_reconnect_success_total 1325
telemt_me_reader_eof_total 1238
telemt_me_idle_close_by_peer_total 1238
telemt_me_route_drop_no_conn_total 2328080
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4420357
telemt_me_endpoint_quarantine_total 572
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 690
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
telemt_me_writers_active_current 46
telemt_desync_total 22243
telemt_desync_full_logged_total 7734
telemt_desync_suppressed_total 14509
telemt_desync_frames_bucket_total{bucket="1_2"} 4247
telemt_desync_frames_bucket_total{bucket="3_10"} 8634
telemt_desync_frames_bucket_total{bucket="gt_10"} 9362
telemt_pool_swap_total 94
telemt_pool_force_close_total 2760
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 356
telemt_me_draining_writers_reap_progress_total 31324
telemt_me_writer_removed_unexpected_total 1229
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3189
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29378
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2392
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28564
telemt_me_writer_teardown_success_total{mode="normal"} 32567
telemt_me_writer_teardown_noop_total 31325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63892
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.619909
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63892
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 356
telemt_me_refill_failed_total 601
telemt_me_writer_restored_same_endpoint_total 1110
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 1516
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 4413679
telemt_user_connections_current{user="hello"} 1934
telemt_user_octets_from_client{user="hello"} 117279688700 (109.23 GB)
telemt_user_octets_to_client{user="hello"} 1795715242562 (1.63 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 941
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 29530.1 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3495117
telemt_connections_bad_total 124456
telemt_connections_current 1740
telemt_connections_me_current 1740
telemt_handshake_timeouts_total 1477724
telemt_upstream_connect_attempt_total 10060
telemt_upstream_connect_success_total 9936
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 10054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_reconnect_attempts_total 2367
telemt_me_reconnect_success_total 335
telemt_me_reader_eof_total 252
telemt_me_idle_close_by_peer_total 252
telemt_me_route_drop_no_conn_total 971188
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1675640
telemt_me_endpoint_quarantine_total 151
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 219
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_writers_active_current 45
telemt_desync_total 9227
telemt_desync_full_logged_total 3112
telemt_desync_suppressed_total 6115
telemt_desync_frames_bucket_total{bucket="1_2"} 1646
telemt_desync_frames_bucket_total{bucket="3_10"} 3525
telemt_desync_frames_bucket_total{bucket="gt_10"} 4056
telemt_pool_swap_total 31
telemt_pool_force_close_total 997
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 95
telemt_me_draining_writers_reap_progress_total 8802
telemt_me_writer_removed_unexpected_total 272
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 783
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8303
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 878
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7805
telemt_me_writer_teardown_success_total{mode="normal"} 9086
telemt_me_writer_teardown_noop_total 8803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17889
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.602084
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17889
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 95
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 274
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 690
telemt_user_connections_total{user="hello"} 1670832
telemt_user_connections_current{user="hello"} 1740
telemt_user_octets_from_client{user="hello"} 48434390228 (45.11 GB)
telemt_user_octets_to_client{user="hello"} 719683484476 (670.26 GB)
telemt_user_unique_ips_current{user="hello"} 815
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 10501.2 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126939
telemt_connections_bad_total 1319
telemt_connections_current 446
telemt_connections_me_current 446
telemt_handshake_timeouts_total 3296
telemt_upstream_connect_attempt_total 4542
telemt_upstream_connect_success_total 4529
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 4541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2584
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 98
telemt_me_reconnect_success_total 50
telemt_me_reader_eof_total 51
telemt_me_idle_close_by_peer_total 51
telemt_me_route_drop_no_conn_total 36062
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109869
telemt_me_endpoint_quarantine_total 81
telemt_me_single_endpoint_shadow_rotate_total 93
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 908
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 688
telemt_desync_frames_bucket_total{bucket="1_2"} 375
telemt_desync_frames_bucket_total{bucket="3_10"} 324
telemt_desync_frames_bucket_total{bucket="gt_10"} 209
telemt_pool_swap_total 11
telemt_pool_force_close_total 279
telemt_me_writer_close_signal_drop_total 13
telemt_me_draining_writers_reap_progress_total 4005
telemt_me_writer_removed_unexpected_total 51
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 254
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3802
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 277
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3726
telemt_me_writer_teardown_success_total{mode="normal"} 4056
telemt_me_writer_teardown_noop_total 4005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8061
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.545720
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8061
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 13
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 109708
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 2225277428 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 66908085996 (62.31 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 92698.7 (25h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6780526
telemt_connections_bad_total 684766
telemt_connections_current 2358
telemt_connections_me_current 2358
telemt_handshake_timeouts_total 194377
telemt_upstream_connect_attempt_total 35058
telemt_upstream_connect_success_total 34918
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 35021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17588
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_reconnect_attempts_total 1428
telemt_me_reconnect_success_total 731
telemt_me_reader_eof_total 708
telemt_me_idle_close_by_peer_total 708
telemt_me_route_drop_no_conn_total 2063787
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5175868
telemt_me_endpoint_quarantine_total 615
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 706
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 19843
telemt_desync_full_logged_total 6619
telemt_desync_suppressed_total 13224
telemt_desync_frames_bucket_total{bucket="1_2"} 4839
telemt_desync_frames_bucket_total{bucket="3_10"} 7228
telemt_desync_frames_bucket_total{bucket="gt_10"} 7776
telemt_pool_swap_total 102
telemt_pool_force_close_total 2794
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 346
telemt_me_draining_writers_reap_progress_total 31497
telemt_me_writer_removed_unexpected_total 688
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2543
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29652
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2709
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28703
telemt_me_writer_teardown_success_total{mode="normal"} 32195
telemt_me_writer_teardown_noop_total 31499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63694
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.204412
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63694
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 346
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 654
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 5151355
telemt_user_connections_current{user="hello"} 2358
telemt_user_octets_from_client{user="hello"} 104015765336 (96.87 GB)
telemt_user_octets_to_client{user="hello"} 2419595366568 (2.20 TB)
telemt_user_unique_ips_current{user="hello"} 961
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 92695.4 (25h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5778814
telemt_connections_bad_total 547901
telemt_connections_current 2216
telemt_connections_me_current 2216
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 162907
telemt_upstream_connect_attempt_total 51194
telemt_upstream_connect_success_total 50809
telemt_upstream_connect_fail_total 326
telemt_upstream_connect_attempts_per_request{bucket="1"} 51135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 326
telemt_me_reconnect_attempts_total 5214
telemt_me_reconnect_success_total 1038
telemt_me_reader_eof_total 915
telemt_me_idle_close_by_peer_total 915
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2116367
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4541534
telemt_me_endpoint_quarantine_total 723
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 702
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
telemt_desync_total 18495
telemt_desync_full_logged_total 6248
telemt_desync_suppressed_total 12247
telemt_desync_frames_bucket_total{bucket="1_2"} 4611
telemt_desync_frames_bucket_total{bucket="3_10"} 6746
telemt_desync_frames_bucket_total{bucket="gt_10"} 7138
telemt_pool_swap_total 100
telemt_pool_force_close_total 2749
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 30454
telemt_me_writer_removed_unexpected_total 925
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3047
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28375
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2528
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 221
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27705
telemt_me_writer_teardown_success_total{mode="normal"} 31422
telemt_me_writer_teardown_noop_total 30458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61880
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.353821
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61880
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 801
telemt_me_writer_restored_fallback_total 49
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 4545129
telemt_user_connections_current{user="hello"} 2216
telemt_user_octets_from_client{user="hello"} 87306235473 (81.31 GB)
telemt_user_octets_to_client{user="hello"} 1947577874392 (1.77 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 961
telemt_user_unique_ips_recent_window{user="hello"} 231
```