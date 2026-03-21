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

# Server Metrics 2026-03-21 16:39:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 72228.6 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2595420
telemt_connections_bad_total 154255
telemt_connections_current 1283
telemt_connections_me_current 1283
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 81133
telemt_upstream_connect_attempt_total 30411
telemt_upstream_connect_success_total 30279
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 30368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1745
telemt_me_reconnect_success_total 688
telemt_me_reader_eof_total 661
telemt_me_idle_close_by_peer_total 661
telemt_me_route_drop_no_conn_total 2214482
telemt_me_route_drop_channel_closed_total 691
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2071643
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 499
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 562
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
telemt_me_writers_active_current 44
telemt_desync_total 8248
telemt_desync_full_logged_total 2853
telemt_desync_suppressed_total 5395
telemt_desync_frames_bucket_total{bucket="1_2"} 1800
telemt_desync_frames_bucket_total{bucket="3_10"} 3143
telemt_desync_frames_bucket_total{bucket="gt_10"} 3305
telemt_pool_swap_total 78
telemt_pool_force_close_total 2363
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 535
telemt_me_draining_writers_reap_progress_total 24489
telemt_me_writer_removed_unexpected_total 639
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2105
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22807
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22126
telemt_me_writer_teardown_success_total{mode="normal"} 24912
telemt_me_writer_teardown_noop_total 24496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49408
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 235.622236
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49408
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 535
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 589
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2072843
telemt_user_connections_current{user="hello"} 1283
telemt_user_octets_from_client{user="hello"} 29554551077 (27.52 GB)
telemt_user_octets_to_client{user="hello"} 511254313182 (476.14 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 489
telemt_user_unique_ips_recent_window{user="hello"} 390
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 3353.6 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201425
telemt_connections_bad_total 7742
telemt_connections_current 2632
telemt_connections_me_current 2632
telemt_handshake_timeouts_total 4717
telemt_upstream_connect_attempt_total 1346
telemt_upstream_connect_success_total 1345
telemt_upstream_connect_attempts_per_request{bucket="1"} 1345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 13
telemt_me_reconnect_success_total 11
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 164389
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177541
telemt_me_endpoint_quarantine_total 23
telemt_me_single_endpoint_shadow_rotate_total 32
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_desync_total 658
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 354
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 263
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 3
telemt_pool_force_close_total 56
telemt_me_writer_close_signal_drop_total 25
telemt_me_draining_writers_reap_progress_total 1167
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 90
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1088
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1111
telemt_me_writer_teardown_success_total{mode="normal"} 1178
telemt_me_writer_teardown_noop_total 1167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2345
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.287758
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2345
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 25
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 174998
telemt_user_connections_current{user="hello"} 2632
telemt_user_octets_from_client{user="hello"} 1548370492 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 36146516848 (33.66 GB)
telemt_user_unique_ips_current{user="hello"} 1332
telemt_user_unique_ips_recent_window{user="hello"} 572
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 72226.1 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5392615
telemt_connections_bad_total 454322
telemt_connections_current 3954
telemt_connections_me_current 3954
telemt_handshake_timeouts_total 179112
telemt_upstream_connect_attempt_total 26555
telemt_upstream_connect_success_total 26497
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 26503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14465
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1178
telemt_me_reconnect_success_total 599
telemt_me_reader_eof_total 603
telemt_me_idle_close_by_peer_total 603
telemt_me_route_drop_no_conn_total 3365009
telemt_me_route_drop_channel_closed_total 47
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4440210
telemt_me_endpoint_quarantine_total 454
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 540
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_desync_total 18038
telemt_desync_full_logged_total 6058
telemt_desync_suppressed_total 11980
telemt_desync_frames_bucket_total{bucket="1_2"} 3813
telemt_desync_frames_bucket_total{bucket="3_10"} 7167
telemt_desync_frames_bucket_total{bucket="gt_10"} 7058
telemt_pool_swap_total 77
telemt_pool_force_close_total 2557
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 407
telemt_me_draining_writers_reap_progress_total 24148
telemt_me_writer_removed_unexpected_total 583
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2119
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22306
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2348
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 209
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21591
telemt_me_writer_teardown_success_total{mode="normal"} 24425
telemt_me_writer_teardown_noop_total 24182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48607
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 100.369659
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48607
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 407
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 540
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 4434872
telemt_user_connections_current{user="hello"} 3954
telemt_user_octets_from_client{user="hello"} 69168298420 (64.42 GB)
telemt_user_octets_to_client{user="hello"} 1399750526516 (1.27 TB)
telemt_user_unique_ips_current{user="hello"} 1541
telemt_user_unique_ips_recent_window{user="hello"} 671
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 72231.3 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4293714
telemt_connections_bad_total 442832
telemt_connections_current 3812
telemt_connections_me_current 3812
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 147600
telemt_upstream_connect_attempt_total 30913
telemt_upstream_connect_success_total 30625
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 30766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 497
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1418
telemt_me_reconnect_success_total 621
telemt_me_reader_eof_total 586
telemt_me_idle_close_by_peer_total 586
telemt_me_route_drop_no_conn_total 1374208
telemt_me_route_drop_channel_closed_total 111
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3180116
telemt_me_endpoint_quarantine_total 456
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 549
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
telemt_me_writers_active_current 43
telemt_desync_total 15205
telemt_desync_full_logged_total 5020
telemt_desync_suppressed_total 10185
telemt_desync_frames_bucket_total{bucket="1_2"} 3772
telemt_desync_frames_bucket_total{bucket="3_10"} 5888
telemt_desync_frames_bucket_total{bucket="gt_10"} 5545
telemt_pool_swap_total 79
telemt_pool_force_close_total 2321
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 240
telemt_me_draining_writers_reap_progress_total 23248
telemt_me_writer_removed_unexpected_total 567
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2006
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21789
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2159
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 162
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20927
telemt_me_writer_teardown_success_total{mode="normal"} 23795
telemt_me_writer_teardown_noop_total 23251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47046
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.420086
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47046
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 240
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 525
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 3179254
telemt_user_connections_current{user="hello"} 3812
telemt_user_octets_from_client{user="hello"} 72354615045 (67.39 GB)
telemt_user_octets_to_client{user="hello"} 1457234878987 (1.33 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1339
telemt_user_unique_ips_recent_window{user="hello"} 729
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 72194.7 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4237538
telemt_connections_bad_total 424474
telemt_connections_current 3240
telemt_connections_me_current 3240
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 127883
telemt_upstream_connect_attempt_total 36172
telemt_upstream_connect_success_total 35928
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 36061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 867
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1502
telemt_me_reconnect_success_total 675
telemt_me_reader_eof_total 620
telemt_me_idle_close_by_peer_total 620
telemt_me_route_drop_no_conn_total 1502777
telemt_me_route_drop_channel_closed_total 49
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3160240
telemt_me_endpoint_quarantine_total 507
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 542
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
telemt_me_writers_active_current 41
telemt_desync_total 14683
telemt_desync_full_logged_total 4821
telemt_desync_suppressed_total 9862
telemt_desync_frames_bucket_total{bucket="1_2"} 3637
telemt_desync_frames_bucket_total{bucket="3_10"} 5533
telemt_desync_frames_bucket_total{bucket="gt_10"} 5513
telemt_pool_swap_total 77
telemt_pool_force_close_total 2242
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 266
telemt_me_draining_writers_reap_progress_total 24660
telemt_me_writer_removed_unexpected_total 589
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2096
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23176
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2052
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 190
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22418
telemt_me_writer_teardown_success_total{mode="normal"} 25272
telemt_me_writer_teardown_noop_total 24667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49939
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.178864
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49939
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 266
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 582
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 3163428
telemt_user_connections_current{user="hello"} 3240
telemt_user_octets_from_client{user="hello"} 78308564265 (72.93 GB)
telemt_user_octets_to_client{user="hello"} 1455579865532 (1.32 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1149
telemt_user_unique_ips_recent_window{user="hello"} 765
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 72245.8 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14675430
telemt_connections_bad_total 946217
telemt_connections_current 5596
telemt_connections_me_current 5596
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 428993
telemt_upstream_connect_attempt_total 117301
telemt_upstream_connect_success_total 107357
telemt_upstream_connect_fail_total 8862
telemt_upstream_connect_attempts_per_request{bucket="1"} 116219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26283
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5370
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8862
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 3913
telemt_me_reconnect_success_total 1438
telemt_me_reader_eof_total 1006
telemt_me_idle_close_by_peer_total 1005
telemt_me_route_drop_no_conn_total 29134154
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12120094
telemt_me_endpoint_quarantine_total 546
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 565
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 21383
telemt_desync_full_logged_total 6590
telemt_desync_suppressed_total 14793
telemt_desync_frames_bucket_total{bucket="1_2"} 4693
telemt_desync_frames_bucket_total{bucket="3_10"} 9319
telemt_desync_frames_bucket_total{bucket="gt_10"} 7371
telemt_pool_swap_total 74
telemt_pool_force_close_total 2438
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 532
telemt_me_draining_writers_reap_progress_total 22950
telemt_me_writer_removed_unexpected_total 1367
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2988
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21090
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2055
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 383
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20512
telemt_me_writer_teardown_success_total{mode="normal"} 24078
telemt_me_writer_teardown_noop_total 22962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47040
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 179.260240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47040
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 532
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1009
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 348
telemt_user_connections_total{user="hello"} 12194519
telemt_user_connections_current{user="hello"} 5596
telemt_user_octets_from_client{user="hello"} 98196661285 (91.45 GB)
telemt_user_octets_to_client{user="hello"} 835814195521 (778.41 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 1967
telemt_user_unique_ips_recent_window{user="hello"} 1239
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 72198.3 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4235613
telemt_connections_bad_total 450345
telemt_connections_current 4054
telemt_connections_me_current 4054
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 89439
telemt_upstream_connect_attempt_total 30080
telemt_upstream_connect_success_total 29716
telemt_upstream_connect_fail_total 316
telemt_upstream_connect_attempts_per_request{bucket="1"} 30032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 316
telemt_me_reconnect_attempts_total 3107
telemt_me_reconnect_success_total 1080
telemt_me_reader_eof_total 1068
telemt_me_idle_close_by_peer_total 1068
telemt_me_route_drop_no_conn_total 1816646
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3273662
telemt_me_endpoint_quarantine_total 442
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 536
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
telemt_me_writers_active_current 49
telemt_desync_total 15859
telemt_desync_full_logged_total 5501
telemt_desync_suppressed_total 10358
telemt_desync_frames_bucket_total{bucket="1_2"} 3095
telemt_desync_frames_bucket_total{bucket="3_10"} 6285
telemt_desync_frames_bucket_total{bucket="gt_10"} 6479
telemt_pool_swap_total 72
telemt_pool_force_close_total 2109
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 214
telemt_me_draining_writers_reap_progress_total 25229
telemt_me_writer_removed_unexpected_total 1035
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2535
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23765
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1803
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23120
telemt_me_writer_teardown_success_total{mode="normal"} 26300
telemt_me_writer_teardown_noop_total 25230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51530
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.649310
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51530
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 214
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 931
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 3256614
telemt_user_connections_current{user="hello"} 4054
telemt_user_octets_from_client{user="hello"} 85177352456 (79.33 GB)
telemt_user_octets_to_client{user="hello"} 1335708058994 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1719
telemt_user_unique_ips_recent_window{user="hello"} 554
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 9033.9 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1382703
telemt_connections_bad_total 48711
telemt_connections_current 3678
telemt_connections_me_current 3678
telemt_handshake_timeouts_total 638724
telemt_upstream_connect_attempt_total 3017
telemt_upstream_connect_success_total 2962
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 3010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1606
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 416
telemt_me_reconnect_success_total 109
telemt_me_reader_eof_total 102
telemt_me_idle_close_by_peer_total 102
telemt_me_route_drop_no_conn_total 506985
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 639171
telemt_me_endpoint_quarantine_total 36
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 65
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
telemt_me_writers_warm_current 3
telemt_desync_total 3468
telemt_desync_full_logged_total 1086
telemt_desync_suppressed_total 2382
telemt_desync_frames_bucket_total{bucket="1_2"} 657
telemt_desync_frames_bucket_total{bucket="3_10"} 1272
telemt_desync_frames_bucket_total{bucket="gt_10"} 1539
telemt_pool_swap_total 8
telemt_pool_force_close_total 264
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 2551
telemt_me_writer_removed_unexpected_total 103
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 231
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2423
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2287
telemt_me_writer_teardown_success_total{mode="normal"} 2654
telemt_me_writer_teardown_noop_total 2551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5205
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.829213
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5205
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 91
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 638269
telemt_user_connections_current{user="hello"} 3678
telemt_user_octets_from_client{user="hello"} 15462704744 (14.40 GB)
telemt_user_octets_to_client{user="hello"} 241137846688 (224.58 GB)
telemt_user_unique_ips_current{user="hello"} 1467
telemt_user_unique_ips_recent_window{user="hello"} 502
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 70184.3 (19h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1340031
telemt_connections_bad_total 148799
telemt_connections_current 828
telemt_connections_me_current 828
telemt_handshake_timeouts_total 474553
telemt_upstream_connect_attempt_total 32374
telemt_upstream_connect_success_total 32365
telemt_upstream_connect_attempts_per_request{bucket="1"} 32365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1371
telemt_me_reconnect_success_total 578
telemt_me_reader_eof_total 578
telemt_me_idle_close_by_peer_total 578
telemt_me_route_drop_no_conn_total 296965
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636384
telemt_me_endpoint_quarantine_total 616
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 583
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 3804
telemt_desync_full_logged_total 1364
telemt_desync_suppressed_total 2440
telemt_desync_frames_bucket_total{bucket="1_2"} 724
telemt_desync_frames_bucket_total{bucket="3_10"} 1354
telemt_desync_frames_bucket_total{bucket="gt_10"} 1726
telemt_pool_swap_total 76
telemt_pool_force_close_total 1799
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 28994
telemt_me_writer_removed_unexpected_total 546
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2198
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27360
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1769
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27195
telemt_me_writer_teardown_success_total{mode="normal"} 29558
telemt_me_writer_teardown_noop_total 28994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58552
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.770859
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58552
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 482
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 635942
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 13108714715 (12.21 GB)
telemt_user_octets_to_client{user="hello"} 245747111885 (228.87 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 72202.6 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4734100
telemt_connections_bad_total 440425
telemt_connections_current 3698
telemt_connections_me_current 3698
telemt_handshake_timeouts_total 156766
telemt_upstream_connect_attempt_total 28409
telemt_upstream_connect_success_total 28291
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14254
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_reconnect_attempts_total 1208
telemt_me_reconnect_success_total 636
telemt_me_reader_eof_total 605
telemt_me_idle_close_by_peer_total 605
telemt_me_route_drop_no_conn_total 1450899
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3742737
telemt_me_endpoint_quarantine_total 514
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 552
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
telemt_desync_total 14583
telemt_desync_full_logged_total 4820
telemt_desync_suppressed_total 9763
telemt_desync_frames_bucket_total{bucket="1_2"} 3446
telemt_desync_frames_bucket_total{bucket="3_10"} 5419
telemt_desync_frames_bucket_total{bucket="gt_10"} 5718
telemt_pool_swap_total 80
telemt_pool_force_close_total 2122
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 249
telemt_me_draining_writers_reap_progress_total 25484
telemt_me_writer_removed_unexpected_total 591
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2055
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24024
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2071
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23362
telemt_me_writer_teardown_success_total{mode="normal"} 26079
telemt_me_writer_teardown_noop_total 25485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51564
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.384144
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51564
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 249
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 565
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3733057
telemt_user_connections_current{user="hello"} 3698
telemt_user_octets_from_client{user="hello"} 74159067948 (69.07 GB)
telemt_user_octets_to_client{user="hello"} 1746274694532 (1.59 TB)
telemt_user_unique_ips_current{user="hello"} 1214
telemt_user_unique_ips_recent_window{user="hello"} 1131
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 72199.5 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4168117
telemt_connections_bad_total 375365
telemt_connections_current 4609
telemt_connections_me_current 4609
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 128787
telemt_upstream_connect_attempt_total 44896
telemt_upstream_connect_success_total 44578
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 44840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16112
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 602
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_reconnect_attempts_total 4124
telemt_me_reconnect_success_total 908
telemt_me_reader_eof_total 788
telemt_me_idle_close_by_peer_total 788
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1529108
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3324906
telemt_me_endpoint_quarantine_total 604
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 548
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 13041
telemt_desync_full_logged_total 4406
telemt_desync_suppressed_total 8635
telemt_desync_frames_bucket_total{bucket="1_2"} 3252
telemt_desync_frames_bucket_total{bucket="3_10"} 4840
telemt_desync_frames_bucket_total{bucket="gt_10"} 4949
telemt_pool_swap_total 78
telemt_pool_force_close_total 2036
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 229
telemt_me_draining_writers_reap_progress_total 24809
telemt_me_writer_removed_unexpected_total 801
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2448
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23195
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1861
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 175
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22773
telemt_me_writer_teardown_success_total{mode="normal"} 25643
telemt_me_writer_teardown_noop_total 24810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50453
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.681725
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50453
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 229
telemt_me_refill_failed_total 183
telemt_me_writer_restored_same_endpoint_total 697
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 3332735
telemt_user_connections_current{user="hello"} 4609
telemt_user_octets_from_client{user="hello"} 60275283493 (56.14 GB)
telemt_user_octets_to_client{user="hello"} 1411474915664 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1826
telemt_user_unique_ips_recent_window{user="hello"} 869
```