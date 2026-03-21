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

# Server Metrics 2026-03-21 19:47:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 83519.2 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3011936
telemt_connections_bad_total 175907
telemt_connections_current 1076
telemt_connections_me_current 1076
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 92167
telemt_upstream_connect_attempt_total 34187
telemt_upstream_connect_success_total 34044
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 34144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 1855
telemt_me_reconnect_success_total 745
telemt_me_reader_eof_total 713
telemt_me_idle_close_by_peer_total 713
telemt_me_route_drop_no_conn_total 2603163
telemt_me_route_drop_channel_closed_total 837
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2434440
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 563
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 650
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 9671
telemt_desync_full_logged_total 3384
telemt_desync_suppressed_total 6287
telemt_desync_frames_bucket_total{bucket="1_2"} 2107
telemt_desync_frames_bucket_total{bucket="3_10"} 3668
telemt_desync_frames_bucket_total{bucket="gt_10"} 3896
telemt_pool_swap_total 90
telemt_pool_force_close_total 2737
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 629
telemt_me_draining_writers_reap_progress_total 27953
telemt_me_writer_removed_unexpected_total 695
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2356
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26034
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2598
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 139
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25216
telemt_me_writer_teardown_success_total{mode="normal"} 28390
telemt_me_writer_teardown_noop_total 27961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56351
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 292.706741
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56351
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 629
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 639
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 2434149
telemt_user_connections_current{user="hello"} 1076
telemt_user_octets_from_client{user="hello"} 36092142545 (33.61 GB)
telemt_user_octets_to_client{user="hello"} 609091831170 (567.26 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 452
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 8656.8 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365374
telemt_connections_bad_total 16780
telemt_connections_current 1090
telemt_connections_me_current 1090
telemt_handshake_timeouts_total 12326
telemt_upstream_connect_attempt_total 3461
telemt_upstream_connect_success_total 3383
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 3450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1901
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 164
telemt_me_reconnect_success_total 119
telemt_me_reader_eof_total 94
telemt_me_idle_close_by_peer_total 94
telemt_me_route_drop_no_conn_total 239138
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300768
telemt_me_endpoint_quarantine_total 75
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 1301
telemt_desync_full_logged_total 730
telemt_desync_suppressed_total 571
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 485
telemt_desync_frames_bucket_total{bucket="gt_10"} 554
telemt_pool_swap_total 9
telemt_pool_force_close_total 280
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 2977
telemt_me_writer_removed_unexpected_total 89
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 263
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2795
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 273
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2697
telemt_me_writer_teardown_success_total{mode="normal"} 3058
telemt_me_writer_teardown_noop_total 2977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6035
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.394802
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6035
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 79
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 300425
telemt_user_connections_current{user="hello"} 1090
telemt_user_octets_from_client{user="hello"} 4947826460 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 83346904464 (77.62 GB)
telemt_user_unique_ips_current{user="hello"} 670
telemt_user_unique_ips_recent_window{user="hello"} 360
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 83517.4 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6599962
telemt_connections_bad_total 509243
telemt_connections_current 3843
telemt_connections_me_current 3843
telemt_handshake_timeouts_total 208933
telemt_upstream_connect_attempt_total 30037
telemt_upstream_connect_success_total 29977
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 29983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1255
telemt_me_reconnect_success_total 652
telemt_me_reader_eof_total 661
telemt_me_idle_close_by_peer_total 661
telemt_me_route_drop_no_conn_total 4201377
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5435123
telemt_me_endpoint_quarantine_total 516
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 621
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 22153
telemt_desync_full_logged_total 7384
telemt_desync_suppressed_total 14769
telemt_desync_frames_bucket_total{bucket="1_2"} 4659
telemt_desync_frames_bucket_total{bucket="3_10"} 8825
telemt_desync_frames_bucket_total{bucket="gt_10"} 8669
telemt_pool_swap_total 89
telemt_pool_force_close_total 2987
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 486
telemt_me_draining_writers_reap_progress_total 27346
telemt_me_writer_removed_unexpected_total 636
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2365
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25267
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2757
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24359
telemt_me_writer_teardown_success_total{mode="normal"} 27632
telemt_me_writer_teardown_noop_total 27383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55015
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 129.159152
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55015
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 486
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 588
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 5428575
telemt_user_connections_current{user="hello"} 3843
telemt_user_octets_from_client{user="hello"} 90894377712 (84.65 GB)
telemt_user_octets_to_client{user="hello"} 1693975327312 (1.54 TB)
telemt_user_unique_ips_current{user="hello"} 1571
telemt_user_unique_ips_recent_window{user="hello"} 467
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 83519.0 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5337864
telemt_connections_bad_total 501691
telemt_connections_current 3688
telemt_connections_me_current 3688
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 176505
telemt_upstream_connect_attempt_total 34256
telemt_upstream_connect_success_total 33943
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 34102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16181
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 540
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1624
telemt_me_reconnect_success_total 683
telemt_me_reader_eof_total 654
telemt_me_idle_close_by_peer_total 654
telemt_me_route_drop_no_conn_total 1854758
telemt_me_route_drop_channel_closed_total 208
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4003765
telemt_me_endpoint_quarantine_total 515
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 635
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 18756
telemt_desync_full_logged_total 6224
telemt_desync_suppressed_total 12532
telemt_desync_frames_bucket_total{bucket="1_2"} 4536
telemt_desync_frames_bucket_total{bucket="3_10"} 7278
telemt_desync_frames_bucket_total{bucket="gt_10"} 6942
telemt_pool_swap_total 91
telemt_pool_force_close_total 2754
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 307
telemt_me_draining_writers_reap_progress_total 26233
telemt_me_writer_removed_unexpected_total 634
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2280
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24515
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2568
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 186
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23479
telemt_me_writer_teardown_success_total{mode="normal"} 26795
telemt_me_writer_teardown_noop_total 26238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53033
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 38.951352
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53033
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 307
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 583
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 4000929
telemt_user_connections_current{user="hello"} 3688
telemt_user_octets_from_client{user="hello"} 118248989277 (110.13 GB)
telemt_user_octets_to_client{user="hello"} 1813608333739 (1.65 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1437
telemt_user_unique_ips_recent_window{user="hello"} 431
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 83482.2 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5270717
telemt_connections_bad_total 474459
telemt_connections_current 3393
telemt_connections_me_current 3393
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 159316
telemt_upstream_connect_attempt_total 40630
telemt_upstream_connect_success_total 40366
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 40500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1704
telemt_me_reconnect_success_total 740
telemt_me_reader_eof_total 684
telemt_me_idle_close_by_peer_total 684
telemt_me_route_drop_no_conn_total 1915595
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3982394
telemt_me_endpoint_quarantine_total 564
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 623
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 18586
telemt_desync_full_logged_total 6048
telemt_desync_suppressed_total 12538
telemt_desync_frames_bucket_total{bucket="1_2"} 4606
telemt_desync_frames_bucket_total{bucket="3_10"} 7051
telemt_desync_frames_bucket_total{bucket="gt_10"} 6929
telemt_pool_swap_total 89
telemt_pool_force_close_total 2622
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 321
telemt_me_draining_writers_reap_progress_total 27626
telemt_me_writer_removed_unexpected_total 653
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25939
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2414
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 208
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25004
telemt_me_writer_teardown_success_total{mode="normal"} 28300
telemt_me_writer_teardown_noop_total 27636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55936
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.913818
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55936
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 321
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 636
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 3985068
telemt_user_connections_current{user="hello"} 3393
telemt_user_octets_from_client{user="hello"} 115275570019 (107.36 GB)
telemt_user_octets_to_client{user="hello"} 1813359904671 (1.65 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1345
telemt_user_unique_ips_recent_window{user="hello"} 445
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 83521.2 (23h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18355111
telemt_connections_bad_total 1156909
telemt_connections_current 4662
telemt_connections_me_current 4662
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 514971
telemt_upstream_connect_attempt_total 173691
telemt_upstream_connect_success_total 156838
telemt_upstream_connect_fail_total 15492
telemt_upstream_connect_attempts_per_request{bucket="1"} 172330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35089
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8816
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15492
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 4591
telemt_me_reconnect_success_total 1717
telemt_me_reader_eof_total 1174
telemt_me_idle_close_by_peer_total 1173
telemt_me_route_drop_no_conn_total 37505679
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15124711
telemt_me_endpoint_quarantine_total 614
telemt_me_single_endpoint_outage_enter_total 98
telemt_me_single_endpoint_outage_exit_total 98
telemt_me_single_endpoint_outage_reconnect_attempt_total 216
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 216
telemt_me_single_endpoint_shadow_rotate_total 647
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_me_writers_active_current 42
telemt_desync_total 27763
telemt_desync_full_logged_total 8252
telemt_desync_suppressed_total 19511
telemt_desync_frames_bucket_total{bucket="1_2"} 5939
telemt_desync_frames_bucket_total{bucket="3_10"} 12404
telemt_desync_frames_bucket_total{bucket="gt_10"} 9420
telemt_pool_swap_total 85
telemt_pool_force_close_total 2826
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 636
telemt_me_draining_writers_reap_progress_total 25792
telemt_me_writer_removed_unexpected_total 1626
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3449
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23727
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2383
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 443
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22966
telemt_me_writer_teardown_success_total{mode="normal"} 27176
telemt_me_writer_teardown_noop_total 25808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52984
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 196.832105
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52984
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 636
telemt_me_refill_failed_total 98
telemt_me_writer_restored_same_endpoint_total 1188
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 160
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 15243673
telemt_user_connections_current{user="hello"} 4662
telemt_user_octets_from_client{user="hello"} 137262780363 (127.84 GB)
telemt_user_octets_to_client{user="hello"} 938879040599 (874.40 GB)
telemt_user_msgs_from_client{user="hello"} 352315
telemt_user_msgs_to_client{user="hello"} 633668
telemt_user_unique_ips_current{user="hello"} 1725
telemt_user_unique_ips_recent_window{user="hello"} 705
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 83489.0 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5219815
telemt_connections_bad_total 508956
telemt_connections_current 3672
telemt_connections_me_current 3672
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 107211
telemt_upstream_connect_attempt_total 43685
telemt_upstream_connect_success_total 43229
telemt_upstream_connect_fail_total 375
telemt_upstream_connect_attempts_per_request{bucket="1"} 43604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17815
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 375
telemt_me_reconnect_attempts_total 3417
telemt_me_reconnect_success_total 1204
telemt_me_reader_eof_total 1178
telemt_me_idle_close_by_peer_total 1178
telemt_me_route_drop_no_conn_total 2202664
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4039325
telemt_me_endpoint_quarantine_total 501
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 619
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
telemt_me_writers_active_current 44
telemt_desync_total 19912
telemt_desync_full_logged_total 6896
telemt_desync_suppressed_total 13016
telemt_desync_frames_bucket_total{bucket="1_2"} 3826
telemt_desync_frames_bucket_total{bucket="3_10"} 7819
telemt_desync_frames_bucket_total{bucket="gt_10"} 8267
telemt_pool_swap_total 84
telemt_pool_force_close_total 2468
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 305
telemt_me_draining_writers_reap_progress_total 28402
telemt_me_writer_removed_unexpected_total 1141
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2886
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26669
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2127
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 341
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25934
telemt_me_writer_teardown_success_total{mode="normal"} 29555
telemt_me_writer_teardown_noop_total 28403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57958
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.661834
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57958
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 305
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 1024
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 4029848
telemt_user_connections_current{user="hello"} 3672
telemt_user_octets_from_client{user="hello"} 107793200109 (100.39 GB)
telemt_user_octets_to_client{user="hello"} 1622773903959 (1.48 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1527
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 20324.7 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2808482
telemt_connections_bad_total 106932
telemt_connections_current 3042
telemt_connections_me_current 3042
telemt_handshake_timeouts_total 1209240
telemt_upstream_connect_attempt_total 6523
telemt_upstream_connect_success_total 6427
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 6517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_reconnect_attempts_total 647
telemt_me_reconnect_success_total 198
telemt_me_reader_eof_total 183
telemt_me_idle_close_by_peer_total 183
telemt_me_route_drop_no_conn_total 849600
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1325616
telemt_me_endpoint_quarantine_total 98
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 149
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 7250
telemt_desync_full_logged_total 2381
telemt_desync_suppressed_total 4869
telemt_desync_frames_bucket_total{bucket="1_2"} 1309
telemt_desync_frames_bucket_total{bucket="3_10"} 2717
telemt_desync_frames_bucket_total{bucket="gt_10"} 3224
telemt_pool_swap_total 21
telemt_pool_force_close_total 676
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 67
telemt_me_draining_writers_reap_progress_total 5665
telemt_me_writer_removed_unexpected_total 180
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 546
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5304
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 590
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 86
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4989
telemt_me_writer_teardown_success_total{mode="normal"} 5850
telemt_me_writer_teardown_noop_total 5665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11515
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.899860
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11515
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 67
telemt_me_refill_failed_total 26
telemt_me_writer_restored_same_endpoint_total 164
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 1322064
telemt_user_connections_current{user="hello"} 3042
telemt_user_octets_from_client{user="hello"} 40942787308 (38.13 GB)
telemt_user_octets_to_client{user="hello"} 530477930568 (494.05 GB)
telemt_user_unique_ips_current{user="hello"} 1250
telemt_user_unique_ips_recent_window{user="hello"} 403
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 1295.7 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11546
telemt_connections_bad_total 17
telemt_connections_current 743
telemt_connections_me_current 743
telemt_handshake_timeouts_total 295
telemt_upstream_connect_attempt_total 613
telemt_upstream_connect_success_total 612
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 2852
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10733
telemt_me_endpoint_quarantine_total 9
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 48
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_draining_writers_reap_progress_total 478
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 454
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 449
telemt_me_writer_teardown_success_total{mode="normal"} 483
telemt_me_writer_teardown_noop_total 478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 961
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.015087
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 961
telemt_me_writer_restored_same_endpoint_total 5
telemt_user_connections_total{user="hello"} 10722
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 570737216 (544.30 MB)
telemt_user_octets_to_client{user="hello"} 9503268504 (8.85 GB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 83493.9 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6081206
telemt_connections_bad_total 573495
telemt_connections_current 4417
telemt_connections_me_current 4417
telemt_handshake_timeouts_total 181438
telemt_upstream_connect_attempt_total 31850
telemt_upstream_connect_success_total 31722
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 31813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_reconnect_attempts_total 1352
telemt_me_reconnect_success_total 691
telemt_me_reader_eof_total 663
telemt_me_idle_close_by_peer_total 663
telemt_me_route_drop_no_conn_total 1913829
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 21
telemt_me_route_drop_queue_full_profile_total{profile="high"} 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4725879
telemt_me_endpoint_quarantine_total 557
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 636
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
telemt_me_writers_active_current 44
telemt_desync_total 17888
telemt_desync_full_logged_total 5909
telemt_desync_suppressed_total 11979
telemt_desync_frames_bucket_total{bucket="1_2"} 4369
telemt_desync_frames_bucket_total{bucket="3_10"} 6546
telemt_desync_frames_bucket_total{bucket="gt_10"} 6973
telemt_pool_swap_total 92
telemt_pool_force_close_total 2498
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 314
telemt_me_draining_writers_reap_progress_total 28592
telemt_me_writer_removed_unexpected_total 648
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2325
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26920
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2428
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26094
telemt_me_writer_teardown_success_total{mode="normal"} 29245
telemt_me_writer_teardown_noop_total 28593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57838
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.292993
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57838
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 314
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 617
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 4702301
telemt_user_connections_current{user="hello"} 4417
telemt_user_octets_from_client{user="hello"} 91846590592 (85.54 GB)
telemt_user_octets_to_client{user="hello"} 2177207988620 (1.98 TB)
telemt_user_unique_ips_current{user="hello"} 1539
telemt_user_unique_ips_recent_window{user="hello"} 534
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 83490.6 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5177699
telemt_connections_bad_total 463047
telemt_connections_current 3436
telemt_connections_me_current 3436
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 151474
telemt_upstream_connect_attempt_total 48222
telemt_upstream_connect_success_total 47868
telemt_upstream_connect_fail_total 295
telemt_upstream_connect_attempts_per_request{bucket="1"} 48163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17818
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 613
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 295
telemt_me_reconnect_attempts_total 4429
telemt_me_reconnect_success_total 972
telemt_me_reader_eof_total 861
telemt_me_idle_close_by_peer_total 861
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 1970509
telemt_me_route_drop_channel_closed_total 180
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4115549
telemt_me_endpoint_quarantine_total 666
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 635
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 16383
telemt_desync_full_logged_total 5542
telemt_desync_suppressed_total 10841
telemt_desync_frames_bucket_total{bucket="1_2"} 4037
telemt_desync_frames_bucket_total{bucket="3_10"} 6048
telemt_desync_frames_bucket_total{bucket="gt_10"} 6298
telemt_pool_swap_total 90
telemt_pool_force_close_total 2433
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 308
telemt_me_draining_writers_reap_progress_total 27815
telemt_me_writer_removed_unexpected_total 872
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2778
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25947
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2242
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 191
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25382
telemt_me_writer_teardown_success_total{mode="normal"} 28725
telemt_me_writer_teardown_noop_total 27817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56542
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.133634
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56542
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 308
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 751
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 4120541
telemt_user_connections_current{user="hello"} 3436
telemt_user_octets_from_client{user="hello"} 76415495397 (71.17 GB)
telemt_user_octets_to_client{user="hello"} 1717699273848 (1.56 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1430
telemt_user_unique_ips_recent_window{user="hello"} 412
```