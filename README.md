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

# Server Metrics 2026-03-22 21:42:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 88551.2 (24h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3227608
telemt_connections_bad_total 237368
telemt_connections_current 935
telemt_connections_me_current 935
telemt_handshake_timeouts_total 103373
telemt_upstream_connect_attempt_total 32498
telemt_upstream_connect_success_total 32497
telemt_upstream_connect_attempts_per_request{bucket="1"} 32497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21191
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1312
telemt_me_reconnect_success_total 543
telemt_me_reader_eof_total 555
telemt_me_idle_close_by_peer_total 555
telemt_me_route_drop_no_conn_total 2845319
telemt_me_route_drop_channel_closed_total 1153
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2716271
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 599
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 689
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
telemt_desync_total 11781
telemt_desync_full_logged_total 3693
telemt_desync_suppressed_total 8088
telemt_desync_frames_bucket_total{bucket="1_2"} 3188
telemt_desync_frames_bucket_total{bucket="3_10"} 4300
telemt_desync_frames_bucket_total{bucket="gt_10"} 4293
telemt_pool_swap_total 98
telemt_pool_force_close_total 3048
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 607
telemt_me_draining_writers_reap_progress_total 29722
telemt_me_writer_removed_unexpected_total 539
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2162
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27801
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2993
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26674
telemt_me_writer_teardown_success_total{mode="normal"} 29963
telemt_me_writer_teardown_noop_total 29733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59696
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 339.612404
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59696
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 607
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 483
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2706198
telemt_user_connections_current{user="hello"} 935
telemt_user_octets_from_client{user="hello"} 39358728088 (36.66 GB)
telemt_user_octets_to_client{user="hello"} 733780146456 (683.39 GB)
telemt_user_unique_ips_current{user="hello"} 411
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 101917.9 (28h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3911463
telemt_connections_bad_total 347256
telemt_connections_current 523
telemt_connections_me_current 523
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99421
telemt_upstream_connect_attempt_total 61023
telemt_upstream_connect_success_total 60280
telemt_upstream_connect_fail_total 657
telemt_upstream_connect_attempts_per_request{bucket="1"} 60937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 657
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 7019
telemt_me_reconnect_success_total 2756
telemt_me_reader_eof_total 2705
telemt_me_idle_close_by_peer_total 2705
telemt_me_route_drop_no_conn_total 3627549
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3118221
telemt_me_endpoint_quarantine_total 770
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 786
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
telemt_me_writers_active_current 86
telemt_me_writers_warm_current 3
telemt_desync_total 12673
telemt_desync_full_logged_total 7101
telemt_desync_suppressed_total 5572
telemt_desync_frames_bucket_total{bucket="1_2"} 2865
telemt_desync_frames_bucket_total{bucket="3_10"} 4975
telemt_desync_frames_bucket_total{bucket="gt_10"} 4833
telemt_pool_swap_total 95
telemt_pool_force_close_total 2879
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 40635
telemt_me_writer_removed_unexpected_total 2646
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4966
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38337
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2452
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37756
telemt_me_writer_teardown_success_total{mode="normal"} 43303
telemt_me_writer_teardown_noop_total 40636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83939
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.389711
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83939
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 171
telemt_me_writer_restored_same_endpoint_total 2430
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 3128884
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 41526201243 (38.67 GB)
telemt_user_octets_to_client{user="hello"} 767305076458 (714.61 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 176778.0 (49h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16112925
telemt_connections_bad_total 1565654
telemt_connections_current 906
telemt_connections_me_current 906
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 395140
telemt_upstream_connect_attempt_total 78410
telemt_upstream_connect_success_total 78310
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 78327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1696
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2848
telemt_me_reconnect_success_total 1481
telemt_me_reader_eof_total 1427
telemt_me_idle_close_by_peer_total 1425
telemt_me_route_drop_no_conn_total 14018155
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12842156
telemt_me_endpoint_quarantine_total 1133
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1321
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
telemt_me_writers_active_current 44
telemt_desync_total 53020
telemt_desync_full_logged_total 16749
telemt_desync_suppressed_total 36271
telemt_desync_frames_bucket_total{bucket="1_2"} 11781
telemt_desync_frames_bucket_total{bucket="3_10"} 20648
telemt_desync_frames_bucket_total{bucket="gt_10"} 20591
telemt_pool_swap_total 191
telemt_pool_force_close_total 6416
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1037
telemt_me_draining_writers_reap_progress_total 58370
telemt_me_writer_removed_unexpected_total 1376
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5107
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53909
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5946
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51954
telemt_me_writer_teardown_success_total{mode="normal"} 59016
telemt_me_writer_teardown_noop_total 58423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117439
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 315.896557
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117439
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1037
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1280
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12842451
telemt_user_connections_current{user="hello"} 906
telemt_user_octets_from_client{user="hello"} 188737458177 (175.78 GB)
telemt_user_octets_to_client{user="hello"} 3443996143335 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 176779.2 (49h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11692783
telemt_connections_bad_total 1189040
telemt_connections_current 902
telemt_connections_me_current 902
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343568
telemt_upstream_connect_attempt_total 92913
telemt_upstream_connect_success_total 91606
telemt_upstream_connect_fail_total 861
telemt_upstream_connect_attempts_per_request{bucket="1"} 92467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37748
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3790
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 861
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4283
telemt_me_reconnect_success_total 1791
telemt_me_reader_eof_total 1650
telemt_me_idle_close_by_peer_total 1650
telemt_me_route_drop_no_conn_total 4533492
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8704491
telemt_me_endpoint_quarantine_total 1133
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1344
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 38471
telemt_desync_full_logged_total 12940
telemt_desync_suppressed_total 25531
telemt_desync_frames_bucket_total{bucket="1_2"} 9495
telemt_desync_frames_bucket_total{bucket="3_10"} 14794
telemt_desync_frames_bucket_total{bucket="gt_10"} 14182
telemt_pool_swap_total 188
telemt_pool_force_close_total 5787
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 56747
telemt_me_writer_removed_unexpected_total 1687
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5243
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53040
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5275
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50960
telemt_me_writer_teardown_success_total{mode="normal"} 58283
telemt_me_writer_teardown_noop_total 56772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115055
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.221084
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115055
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1524
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8642370
telemt_user_connections_current{user="hello"} 902
telemt_user_octets_from_client{user="hello"} 216808448204 (201.92 GB)
telemt_user_octets_to_client{user="hello"} 3914719632455 (3.56 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 176745.7 (49h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10927744
telemt_connections_bad_total 948818
telemt_connections_current 713
telemt_connections_me_current 713
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344687
telemt_upstream_connect_attempt_total 76598
telemt_upstream_connect_success_total 75186
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 75383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36104
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1419
telemt_me_reconnect_attempts_total 5396
telemt_me_reconnect_success_total 2198
telemt_me_reader_eof_total 1934
telemt_me_idle_close_by_peer_total 1933
telemt_me_route_drop_no_conn_total 5313239
telemt_me_route_drop_channel_closed_total 382
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8270429
telemt_me_endpoint_quarantine_total 1219
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1297
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 67
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
telemt_desync_total 37839
telemt_desync_full_logged_total 12537
telemt_desync_suppressed_total 25302
telemt_desync_frames_bucket_total{bucket="1_2"} 9561
telemt_desync_frames_bucket_total{bucket="3_10"} 14473
telemt_desync_frames_bucket_total{bucket="gt_10"} 13805
telemt_pool_swap_total 185
telemt_pool_force_close_total 5722
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 724
telemt_me_draining_writers_reap_progress_total 56871
telemt_me_writer_removed_unexpected_total 2084
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5847
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53034
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5157
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51149
telemt_me_writer_teardown_success_total{mode="normal"} 58881
telemt_me_writer_teardown_noop_total 56942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115823
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.226458
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115823
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 724
telemt_me_refill_failed_total 169
telemt_me_writer_restored_same_endpoint_total 1898
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8262438
telemt_user_connections_current{user="hello"} 713
telemt_user_octets_from_client{user="hello"} 191868990413 (178.69 GB)
telemt_user_octets_to_client{user="hello"} 3437004451501 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 47022.6 (13h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11015969
telemt_connections_bad_total 666748
telemt_connections_current 1290
telemt_connections_me_current 1290
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 246800
telemt_upstream_connect_attempt_total 50609
telemt_upstream_connect_success_total 48069
telemt_upstream_connect_fail_total 1735
telemt_upstream_connect_attempts_per_request{bucket="1"} 49804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15879
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5985
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1735
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7008
telemt_me_reconnect_success_total 1029
telemt_me_reader_eof_total 639
telemt_me_idle_close_by_peer_total 638
telemt_me_route_drop_no_conn_total 25249304
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9148818
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 371
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
telemt_desync_total 15600
telemt_desync_full_logged_total 4126
telemt_desync_suppressed_total 11474
telemt_desync_frames_bucket_total{bucket="1_2"} 2987
telemt_desync_frames_bucket_total{bucket="3_10"} 6313
telemt_desync_frames_bucket_total{bucket="gt_10"} 6300
telemt_pool_swap_total 48
telemt_pool_force_close_total 1687
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 450
telemt_me_draining_writers_reap_progress_total 13786
telemt_me_writer_removed_unexpected_total 916
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2017
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12643
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1381
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12099
telemt_me_writer_teardown_success_total{mode="normal"} 14660
telemt_me_writer_teardown_noop_total 13805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28465
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.142624
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28465
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 450
telemt_me_refill_failed_total 325
telemt_me_writer_restored_same_endpoint_total 669
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 9173529
telemt_user_connections_current{user="hello"} 1290
telemt_user_octets_from_client{user="hello"} 85117102824 (79.27 GB)
telemt_user_octets_to_client{user="hello"} 549816779086 (512.06 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 484
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 176749.3 (49h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10838862
telemt_connections_bad_total 912693
telemt_connections_current 1090
telemt_connections_me_current 1090
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 238405
telemt_upstream_connect_attempt_total 105541
telemt_upstream_connect_success_total 104436
telemt_upstream_connect_fail_total 941
telemt_upstream_connect_attempts_per_request{bucket="1"} 105377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39620
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 941
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72584
telemt_me_reconnect_success_total 2917
telemt_me_reader_eof_total 2613
telemt_me_idle_close_by_peer_total 2611
telemt_me_route_drop_no_conn_total 5233570
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8566625
telemt_me_endpoint_quarantine_total 1161
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1326
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_me_writers_active_current 91
telemt_desync_total 45716
telemt_desync_full_logged_total 15620
telemt_desync_suppressed_total 30096
telemt_desync_frames_bucket_total{bucket="1_2"} 9262
telemt_desync_frames_bucket_total{bucket="3_10"} 17499
telemt_desync_frames_bucket_total{bucket="gt_10"} 18955
telemt_pool_swap_total 180
telemt_pool_force_close_total 5371
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 647
telemt_me_draining_writers_reap_progress_total 60740
telemt_me_writer_removed_unexpected_total 2648
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6425
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56992
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4641
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55369
telemt_me_writer_teardown_success_total{mode="normal"} 63417
telemt_me_writer_teardown_noop_total 60741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124158
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.141850
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124158
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 647
telemt_me_refill_failed_total 4291
telemt_me_writer_restored_same_endpoint_total 2463
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 8569735
telemt_user_connections_current{user="hello"} 1090
telemt_user_octets_from_client{user="hello"} 193429575741 (180.15 GB)
telemt_user_octets_to_client{user="hello"} 3268181850652 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 484
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 113585.4 (31h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11463209
telemt_connections_bad_total 459268
telemt_connections_current 463
telemt_connections_me_current 463
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4696243
telemt_upstream_connect_attempt_total 53648
telemt_upstream_connect_success_total 53252
telemt_upstream_connect_fail_total 386
telemt_upstream_connect_attempts_per_request{bucket="1"} 53638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 386
telemt_me_reconnect_attempts_total 48662
telemt_me_reconnect_success_total 1702
telemt_me_reader_eof_total 1363
telemt_me_idle_close_by_peer_total 1362
telemt_me_route_drop_no_conn_total 4065682
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5529779
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 860
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31036
telemt_desync_full_logged_total 10563
telemt_desync_suppressed_total 20473
telemt_desync_frames_bucket_total{bucket="1_2"} 6164
telemt_desync_frames_bucket_total{bucket="3_10"} 12269
telemt_desync_frames_bucket_total{bucket="gt_10"} 12603
telemt_pool_swap_total 120
telemt_pool_force_close_total 3641
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 364
telemt_me_draining_writers_reap_progress_total 39820
telemt_me_writer_removed_unexpected_total 1421
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3453
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37824
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3200
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36179
telemt_me_writer_teardown_success_total{mode="normal"} 41277
telemt_me_writer_teardown_noop_total 39827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81104
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.622904
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81104
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 364
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1512
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5522448
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 118249506044 (110.13 GB)
telemt_user_octets_to_client{user="hello"} 2121082222286 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 94556.3 (26h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1429870
telemt_connections_bad_total 35349
telemt_connections_current 712
telemt_connections_me_current 712
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 27349
telemt_upstream_connect_attempt_total 44255
telemt_upstream_connect_success_total 44117
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 44228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 757
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2054
telemt_me_reconnect_success_total 839
telemt_me_reader_eof_total 822
telemt_me_idle_close_by_peer_total 822
telemt_me_route_drop_no_conn_total 496549
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1269111
telemt_me_endpoint_quarantine_total 763
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 776
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 20
telemt_desync_total 7908
telemt_desync_full_logged_total 2406
telemt_desync_suppressed_total 5502
telemt_desync_frames_bucket_total{bucket="1_2"} 1910
telemt_desync_frames_bucket_total{bucket="3_10"} 3052
telemt_desync_frames_bucket_total{bucket="gt_10"} 2946
telemt_pool_swap_total 101
telemt_pool_force_close_total 2630
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 36967
telemt_me_writer_removed_unexpected_total 791
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2919
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34873
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2542
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34337
telemt_me_writer_teardown_success_total{mode="normal"} 37792
telemt_me_writer_teardown_noop_total 36971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74763
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.891275
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74763
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 712
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 1265074
telemt_user_connections_current{user="hello"} 712
telemt_user_octets_from_client{user="hello"} 24805027309 (23.10 GB)
telemt_user_octets_to_client{user="hello"} 536648870927 (499.79 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 176754.4 (49h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13172887
telemt_connections_bad_total 1560685
telemt_connections_current 1159
telemt_connections_me_current 1159
telemt_handshake_timeouts_total 378535
telemt_upstream_connect_attempt_total 67368
telemt_upstream_connect_success_total 67031
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 67232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2637
telemt_me_reconnect_success_total 1378
telemt_me_reader_eof_total 1346
telemt_me_idle_close_by_peer_total 1346
telemt_me_route_drop_no_conn_total 4463327
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9956077
telemt_me_endpoint_quarantine_total 1210
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1325
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
telemt_me_writers_active_current 45
telemt_desync_total 41534
telemt_desync_full_logged_total 13544
telemt_desync_suppressed_total 27990
telemt_desync_frames_bucket_total{bucket="1_2"} 9986
telemt_desync_frames_bucket_total{bucket="3_10"} 15292
telemt_desync_frames_bucket_total{bucket="gt_10"} 16256
telemt_pool_swap_total 196
telemt_pool_force_close_total 5357
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 60758
telemt_me_writer_removed_unexpected_total 1295
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4927
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57167
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55401
telemt_me_writer_teardown_success_total{mode="normal"} 62094
telemt_me_writer_teardown_noop_total 60760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122854
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.568559
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122854
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1205
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 9922921
telemt_user_connections_current{user="hello"} 1159
telemt_user_octets_from_client{user="hello"} 193791163364 (180.48 GB)
telemt_user_octets_to_client{user="hello"} 4391007558132 (3.99 TB)
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 176750.7 (49h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11458165
telemt_connections_bad_total 1305440
telemt_connections_current 834
telemt_connections_me_current 834
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 302005
telemt_upstream_connect_attempt_total 93838
telemt_upstream_connect_success_total 92996
telemt_upstream_connect_fail_total 635
telemt_upstream_connect_attempts_per_request{bucket="1"} 93631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2066
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 635
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10047
telemt_me_reconnect_success_total 2423
telemt_me_reader_eof_total 2264
telemt_me_idle_close_by_peer_total 2263
telemt_me_seq_mismatch_total 83
telemt_me_route_drop_no_conn_total 5622726
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8856511
telemt_me_endpoint_quarantine_total 1359
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1328
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
telemt_me_writers_active_current 48
telemt_desync_total 41129
telemt_desync_full_logged_total 13182
telemt_desync_suppressed_total 27947
telemt_desync_frames_bucket_total{bucket="1_2"} 10554
telemt_desync_frames_bucket_total{bucket="3_10"} 15142
telemt_desync_frames_bucket_total{bucket="gt_10"} 15433
telemt_pool_swap_total 186
telemt_pool_force_close_total 5152
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 647
telemt_me_draining_writers_reap_progress_total 60518
telemt_me_writer_removed_unexpected_total 2297
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6267
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56627
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4681
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55366
telemt_me_writer_teardown_success_total{mode="normal"} 62894
telemt_me_writer_teardown_noop_total 60523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123417
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.291789
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123417
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 647
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 1967
telemt_me_writer_restored_fallback_total 115
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 8861963
telemt_user_connections_current{user="hello"} 834
telemt_user_octets_from_client{user="hello"} 156556657777 (145.80 GB)
telemt_user_octets_to_client{user="hello"} 3448789526731 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 97
```