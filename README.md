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

# Server Metrics 2026-03-22 21:06:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 86411.5 (24h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3178481
telemt_connections_bad_total 227395
telemt_connections_current 911
telemt_connections_me_current 911
telemt_handshake_timeouts_total 101512
telemt_upstream_connect_attempt_total 31651
telemt_upstream_connect_success_total 31650
telemt_upstream_connect_attempts_per_request{bucket="1"} 31650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1283
telemt_me_reconnect_success_total 530
telemt_me_reader_eof_total 540
telemt_me_idle_close_by_peer_total 540
telemt_me_route_drop_no_conn_total 2824633
telemt_me_route_drop_channel_closed_total 1137
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2679834
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 583
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 668
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
telemt_desync_total 11564
telemt_desync_full_logged_total 3624
telemt_desync_suppressed_total 7940
telemt_desync_frames_bucket_total{bucket="1_2"} 3125
telemt_desync_frames_bucket_total{bucket="3_10"} 4236
telemt_desync_frames_bucket_total{bucket="gt_10"} 4203
telemt_pool_swap_total 95
telemt_pool_force_close_total 2968
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 603
telemt_me_draining_writers_reap_progress_total 28937
telemt_me_writer_removed_unexpected_total 524
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2107
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27059
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2913
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25969
telemt_me_writer_teardown_success_total{mode="normal"} 29166
telemt_me_writer_teardown_noop_total 28948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58114
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 332.395121
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58114
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 603
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 471
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 2670441
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 39033344204 (36.35 GB)
telemt_user_octets_to_client{user="hello"} 717441777372 (668.17 GB)
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 99777.9 (27h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3887929
telemt_connections_bad_total 343827
telemt_connections_current 671
telemt_connections_me_current 671
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 98750
telemt_upstream_connect_attempt_total 59918
telemt_upstream_connect_success_total 59189
telemt_upstream_connect_fail_total 643
telemt_upstream_connect_attempts_per_request{bucket="1"} 59832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 643
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6874
telemt_me_reconnect_success_total 2684
telemt_me_reader_eof_total 2633
telemt_me_idle_close_by_peer_total 2633
telemt_me_route_drop_no_conn_total 3621942
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3099660
telemt_me_endpoint_quarantine_total 757
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 768
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 12540
telemt_desync_full_logged_total 7024
telemt_desync_suppressed_total 5516
telemt_desync_frames_bucket_total{bucket="1_2"} 2838
telemt_desync_frames_bucket_total{bucket="3_10"} 4925
telemt_desync_frames_bucket_total{bucket="gt_10"} 4777
telemt_pool_swap_total 93
telemt_pool_force_close_total 2827
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 234
telemt_me_draining_writers_reap_progress_total 39730
telemt_me_writer_removed_unexpected_total 2576
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4846
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37480
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2400
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36903
telemt_me_writer_teardown_success_total{mode="normal"} 42326
telemt_me_writer_teardown_noop_total 39731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82057
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.361617
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82057
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 234
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 2366
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 3110359
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 40830341167 (38.03 GB)
telemt_user_octets_to_client{user="hello"} 756549863938 (704.59 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 174637.8 (48h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16060149
telemt_connections_bad_total 1556562
telemt_connections_current 1719
telemt_connections_me_current 1719
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 394353
telemt_upstream_connect_attempt_total 77419
telemt_upstream_connect_success_total 77318
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 77335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37210
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1691
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2836
telemt_me_reconnect_success_total 1472
telemt_me_reader_eof_total 1417
telemt_me_idle_close_by_peer_total 1415
telemt_me_route_drop_no_conn_total 14006201
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12801354
telemt_me_endpoint_quarantine_total 1109
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1300
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 10
telemt_desync_total 52834
telemt_desync_full_logged_total 16676
telemt_desync_suppressed_total 36158
telemt_desync_frames_bucket_total{bucket="1_2"} 11757
telemt_desync_frames_bucket_total{bucket="3_10"} 20586
telemt_desync_frames_bucket_total{bucket="gt_10"} 20491
telemt_pool_swap_total 188
telemt_pool_force_close_total 6331
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1022
telemt_me_draining_writers_reap_progress_total 57436
telemt_me_writer_removed_unexpected_total 1367
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5025
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53057
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5861
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51105
telemt_me_writer_teardown_success_total{mode="normal"} 58082
telemt_me_writer_teardown_noop_total 57487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115569
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.795128
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115569
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1022
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1271
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12801714
telemt_user_connections_current{user="hello"} 1719
telemt_user_octets_from_client{user="hello"} 188248001905 (175.32 GB)
telemt_user_octets_to_client{user="hello"} 3423501509939 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 753
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 174639.8 (48h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11641430
telemt_connections_bad_total 1173843
telemt_connections_current 1104
telemt_connections_me_current 1104
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343405
telemt_upstream_connect_attempt_total 91960
telemt_upstream_connect_success_total 90662
telemt_upstream_connect_fail_total 857
telemt_upstream_connect_attempts_per_request{bucket="1"} 91519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3790
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 857
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4274
telemt_me_reconnect_success_total 1783
telemt_me_reader_eof_total 1641
telemt_me_idle_close_by_peer_total 1641
telemt_me_route_drop_no_conn_total 4525321
telemt_me_route_drop_channel_closed_total 496
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8671624
telemt_me_endpoint_quarantine_total 1104
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1320
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_me_writers_active_current 49
telemt_me_writers_warm_current 10
telemt_desync_total 38376
telemt_desync_full_logged_total 12914
telemt_desync_suppressed_total 25462
telemt_desync_frames_bucket_total{bucket="1_2"} 9480
telemt_desync_frames_bucket_total{bucket="3_10"} 14760
telemt_desync_frames_bucket_total{bucket="gt_10"} 14136
telemt_pool_swap_total 185
telemt_pool_force_close_total 5700
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 705
telemt_me_draining_writers_reap_progress_total 55854
telemt_me_writer_removed_unexpected_total 1679
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5186
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52195
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50154
telemt_me_writer_teardown_success_total{mode="normal"} 57381
telemt_me_writer_teardown_noop_total 55879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113260
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.810278
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113260
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 705
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1516
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8609568
telemt_user_connections_current{user="hello"} 1104
telemt_user_octets_from_client{user="hello"} 216516897192 (201.65 GB)
telemt_user_octets_to_client{user="hello"} 3895735845923 (3.54 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 490
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 174603.8 (48h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10897450
telemt_connections_bad_total 945197
telemt_connections_current 685
telemt_connections_me_current 685
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344496
telemt_upstream_connect_attempt_total 75603
telemt_upstream_connect_success_total 74248
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 74444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1753
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2277
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1419
telemt_me_reconnect_attempts_total 5299
telemt_me_reconnect_success_total 2176
telemt_me_reader_eof_total 1910
telemt_me_idle_close_by_peer_total 1909
telemt_me_route_drop_no_conn_total 5305735
telemt_me_route_drop_channel_closed_total 382
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8245936
telemt_me_endpoint_quarantine_total 1193
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1277
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 66
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
telemt_desync_total 37796
telemt_desync_full_logged_total 12521
telemt_desync_suppressed_total 25275
telemt_desync_frames_bucket_total{bucket="1_2"} 9552
telemt_desync_frames_bucket_total{bucket="3_10"} 14456
telemt_desync_frames_bucket_total{bucket="gt_10"} 13788
telemt_pool_swap_total 182
telemt_pool_force_close_total 5647
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 720
telemt_me_draining_writers_reap_progress_total 56048
telemt_me_writer_removed_unexpected_total 2061
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5764
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52269
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5082
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50401
telemt_me_writer_teardown_success_total{mode="normal"} 58033
telemt_me_writer_teardown_noop_total 56119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114152
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.066793
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114152
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 720
telemt_me_refill_failed_total 165
telemt_me_writer_restored_same_endpoint_total 1880
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 8237977
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 191675003933 (178.51 GB)
telemt_user_octets_to_client{user="hello"} 3427580814213 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 44883.2 (12h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10953443
telemt_connections_bad_total 664381
telemt_connections_current 1566
telemt_connections_me_current 1566
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 242082
telemt_upstream_connect_attempt_total 49672
telemt_upstream_connect_success_total 47160
telemt_upstream_connect_fail_total 1729
telemt_upstream_connect_attempts_per_request{bucket="1"} 48889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15382
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5982
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1729
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6964
telemt_me_reconnect_success_total 1011
telemt_me_reader_eof_total 621
telemt_me_idle_close_by_peer_total 620
telemt_me_route_drop_no_conn_total 25234910
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9096008
telemt_me_endpoint_quarantine_total 310
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 355
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
telemt_me_writers_active_current 43
telemt_desync_total 15114
telemt_desync_full_logged_total 4023
telemt_desync_suppressed_total 11091
telemt_desync_frames_bucket_total{bucket="1_2"} 2833
telemt_desync_frames_bucket_total{bucket="3_10"} 6125
telemt_desync_frames_bucket_total{bucket="gt_10"} 6156
telemt_pool_swap_total 45
telemt_pool_force_close_total 1612
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 445
telemt_me_draining_writers_reap_progress_total 12954
telemt_me_writer_removed_unexpected_total 901
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1948
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11862
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1306
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11342
telemt_me_writer_teardown_success_total{mode="normal"} 13810
telemt_me_writer_teardown_noop_total 12973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26783
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.081209
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26783
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 445
telemt_me_refill_failed_total 324
telemt_me_writer_restored_same_endpoint_total 657
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 9120770
telemt_user_connections_current{user="hello"} 1566
telemt_user_octets_from_client{user="hello"} 84726429088 (78.91 GB)
telemt_user_octets_to_client{user="hello"} 531200661898 (494.72 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 596
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 174609.7 (48h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10794878
telemt_connections_bad_total 909721
telemt_connections_current 1335
telemt_connections_me_current 1335
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 237511
telemt_upstream_connect_attempt_total 104510
telemt_upstream_connect_success_total 103415
telemt_upstream_connect_fail_total 934
telemt_upstream_connect_attempts_per_request{bucket="1"} 104349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 934
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72449
telemt_me_reconnect_success_total 2852
telemt_me_reader_eof_total 2547
telemt_me_idle_close_by_peer_total 2545
telemt_me_route_drop_no_conn_total 5223475
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8531444
telemt_me_endpoint_quarantine_total 1150
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1303
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 45485
telemt_desync_full_logged_total 15523
telemt_desync_suppressed_total 29962
telemt_desync_frames_bucket_total{bucket="1_2"} 9224
telemt_desync_frames_bucket_total{bucket="3_10"} 17422
telemt_desync_frames_bucket_total{bucket="gt_10"} 18839
telemt_pool_swap_total 178
telemt_pool_force_close_total 5319
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 59889
telemt_me_writer_removed_unexpected_total 2583
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6323
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56177
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4589
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54570
telemt_me_writer_teardown_success_total{mode="normal"} 62500
telemt_me_writer_teardown_noop_total 59890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122390
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.110240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122390
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 4287
telemt_me_writer_restored_same_endpoint_total 2401
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 8534630
telemt_user_connections_current{user="hello"} 1335
telemt_user_octets_from_client{user="hello"} 193067639713 (179.81 GB)
telemt_user_octets_to_client{user="hello"} 3253539513820 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 550
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 111445.9 (30h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11408103
telemt_connections_bad_total 456451
telemt_connections_current 942
telemt_connections_me_current 942
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4676960
telemt_upstream_connect_attempt_total 52663
telemt_upstream_connect_success_total 52270
telemt_upstream_connect_fail_total 383
telemt_upstream_connect_attempts_per_request{bucket="1"} 52653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 383
telemt_me_reconnect_attempts_total 48639
telemt_me_reconnect_success_total 1695
telemt_me_reader_eof_total 1355
telemt_me_idle_close_by_peer_total 1354
telemt_me_route_drop_no_conn_total 4056402
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5502199
telemt_me_endpoint_quarantine_total 719
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 841
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30936
telemt_desync_full_logged_total 10514
telemt_desync_suppressed_total 20422
telemt_desync_frames_bucket_total{bucket="1_2"} 6144
telemt_desync_frames_bucket_total{bucket="3_10"} 12242
telemt_desync_frames_bucket_total{bucket="gt_10"} 12550
telemt_pool_swap_total 117
telemt_pool_force_close_total 3562
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 359
telemt_me_draining_writers_reap_progress_total 38904
telemt_me_writer_removed_unexpected_total 1414
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3405
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36948
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3121
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35342
telemt_me_writer_teardown_success_total{mode="normal"} 40353
telemt_me_writer_teardown_noop_total 38911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79264
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.611446
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79264
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 359
telemt_me_refill_failed_total 2728
telemt_me_writer_restored_same_endpoint_total 1506
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5494927
telemt_user_connections_current{user="hello"} 942
telemt_user_octets_from_client{user="hello"} 117857570412 (109.76 GB)
telemt_user_octets_to_client{user="hello"} 2107590576602 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 422
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 92416.9 (25h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1400768
telemt_connections_bad_total 34395
telemt_connections_current 828
telemt_connections_me_current 828
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25919
telemt_upstream_connect_attempt_total 43423
telemt_upstream_connect_success_total 43287
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 43396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 742
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2041
telemt_me_reconnect_success_total 828
telemt_me_reader_eof_total 810
telemt_me_idle_close_by_peer_total 810
telemt_me_route_drop_no_conn_total 487956
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1243034
telemt_me_endpoint_quarantine_total 754
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 761
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
telemt_me_writers_active_current 44
telemt_desync_total 7625
telemt_desync_full_logged_total 2345
telemt_desync_suppressed_total 5280
telemt_desync_frames_bucket_total{bucket="1_2"} 1755
telemt_desync_frames_bucket_total{bucket="3_10"} 2946
telemt_desync_frames_bucket_total{bucket="gt_10"} 2924
telemt_pool_swap_total 99
telemt_pool_force_close_total 2576
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 36253
telemt_me_writer_removed_unexpected_total 780
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2864
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34202
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33677
telemt_me_writer_teardown_success_total{mode="normal"} 37066
telemt_me_writer_teardown_noop_total 36257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73323
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.725786
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73323
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 702
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1239034
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 24156094417 (22.50 GB)
telemt_user_octets_to_client{user="hello"} 523959839519 (487.98 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 174614.3 (48h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13130096
telemt_connections_bad_total 1551189
telemt_connections_current 1310
telemt_connections_me_current 1310
telemt_handshake_timeouts_total 376644
telemt_upstream_connect_attempt_total 66258
telemt_upstream_connect_success_total 65925
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 66123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2582
telemt_me_reconnect_success_total 1359
telemt_me_reader_eof_total 1326
telemt_me_idle_close_by_peer_total 1326
telemt_me_route_drop_no_conn_total 4454792
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9926005
telemt_me_endpoint_quarantine_total 1177
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1307
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
telemt_me_writers_active_current 44
telemt_desync_total 41372
telemt_desync_full_logged_total 13476
telemt_desync_suppressed_total 27896
telemt_desync_frames_bucket_total{bucket="1_2"} 9954
telemt_desync_frames_bucket_total{bucket="3_10"} 15233
telemt_desync_frames_bucket_total{bucket="gt_10"} 16185
telemt_pool_swap_total 193
telemt_pool_force_close_total 5293
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 655
telemt_me_draining_writers_reap_progress_total 59724
telemt_me_writer_removed_unexpected_total 1276
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4850
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56190
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5119
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54431
telemt_me_writer_teardown_success_total{mode="normal"} 61040
telemt_me_writer_teardown_noop_total 59726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120766
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.530944
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120766
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 655
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1190
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 9892912
telemt_user_connections_current{user="hello"} 1310
telemt_user_octets_from_client{user="hello"} 193395084128 (180.11 GB)
telemt_user_octets_to_client{user="hello"} 4376784160640 (3.98 TB)
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 174610.8 (48h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11409150
telemt_connections_bad_total 1290380
telemt_connections_current 986
telemt_connections_me_current 986
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 300483
telemt_upstream_connect_attempt_total 92676
telemt_upstream_connect_success_total 91844
telemt_upstream_connect_fail_total 625
telemt_upstream_connect_attempts_per_request{bucket="1"} 92469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 625
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9929
telemt_me_reconnect_success_total 2393
telemt_me_reader_eof_total 2237
telemt_me_idle_close_by_peer_total 2236
telemt_me_seq_mismatch_total 80
telemt_me_route_drop_no_conn_total 5614805
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8826498
telemt_me_endpoint_quarantine_total 1334
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1307
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
telemt_desync_total 40572
telemt_desync_full_logged_total 13072
telemt_desync_suppressed_total 27500
telemt_desync_frames_bucket_total{bucket="1_2"} 10224
telemt_desync_frames_bucket_total{bucket="3_10"} 15024
telemt_desync_frames_bucket_total{bucket="gt_10"} 15324
telemt_pool_swap_total 183
telemt_pool_force_close_total 5089
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 641
telemt_me_draining_writers_reap_progress_total 59449
telemt_me_writer_removed_unexpected_total 2269
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6194
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55601
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4618
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54360
telemt_me_writer_teardown_success_total{mode="normal"} 61795
telemt_me_writer_teardown_noop_total 59454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121249
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.244076
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121249
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 641
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 1949
telemt_me_writer_restored_fallback_total 111
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 8831992
telemt_user_connections_current{user="hello"} 986
telemt_user_octets_from_client{user="hello"} 156216678629 (145.49 GB)
telemt_user_octets_to_client{user="hello"} 3430325815899 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 125
```