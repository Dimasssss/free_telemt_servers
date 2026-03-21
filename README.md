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

# Server Metrics 2026-03-21 21:35:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 1749.7 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36376
telemt_connections_bad_total 2107
telemt_connections_current 911
telemt_connections_me_current 911
telemt_handshake_timeouts_total 1354
telemt_upstream_connect_attempt_total 689
telemt_upstream_connect_success_total 689
telemt_upstream_connect_attempts_per_request{bucket="1"} 689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 7859
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30201
telemt_me_endpoint_quarantine_total 12
telemt_me_single_endpoint_shadow_rotate_total 16
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
telemt_me_writers_active_current 44
telemt_desync_total 163
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_close_signal_drop_total 2
telemt_me_draining_writers_reap_progress_total 563
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 534
telemt_me_writer_teardown_success_total{mode="normal"} 570
telemt_me_writer_teardown_noop_total 563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1133
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.196546
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1133
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 2
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 30188
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 304354920 (290.26 MB)
telemt_user_octets_to_client{user="hello"} 8536715588 (7.95 GB)
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 15115.9 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 551322
telemt_connections_bad_total 26092
telemt_connections_current 1205
telemt_connections_me_current 1205
telemt_handshake_timeouts_total 19298
telemt_upstream_connect_attempt_total 6012
telemt_upstream_connect_success_total 5896
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 5999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_reconnect_attempts_total 499
telemt_me_reconnect_success_total 188
telemt_me_reader_eof_total 165
telemt_me_idle_close_by_peer_total 165
telemt_me_route_drop_no_conn_total 297872
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445297
telemt_me_endpoint_quarantine_total 119
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 120
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_me_writers_active_current 46
telemt_desync_total 2000
telemt_desync_full_logged_total 1134
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 762
telemt_desync_frames_bucket_total{bucket="gt_10"} 825
telemt_pool_swap_total 16
telemt_pool_force_close_total 476
telemt_me_writer_close_signal_drop_total 38
telemt_me_draining_writers_reap_progress_total 5234
telemt_me_writer_removed_unexpected_total 154
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4928
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 469
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4758
telemt_me_writer_teardown_success_total{mode="normal"} 5386
telemt_me_writer_teardown_noop_total 5234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10620
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.894517
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10620
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 38
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 128
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 444745
telemt_user_connections_current{user="hello"} 1205
telemt_user_octets_from_client{user="hello"} 7241333492 (6.74 GB)
telemt_user_octets_to_client{user="hello"} 144108019016 (134.21 GB)
telemt_user_unique_ips_current{user="hello"} 693
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 89976.1 (24h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7108642
telemt_connections_bad_total 547607
telemt_connections_current 3241
telemt_connections_me_current 3241
telemt_handshake_timeouts_total 222684
telemt_upstream_connect_attempt_total 32285
telemt_upstream_connect_success_total 32221
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 32228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17567
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1396
telemt_me_reconnect_success_total 685
telemt_me_reader_eof_total 696
telemt_me_idle_close_by_peer_total 696
telemt_me_route_drop_no_conn_total 4421122
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5811277
telemt_me_endpoint_quarantine_total 561
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 665
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 24205
telemt_desync_full_logged_total 8031
telemt_desync_suppressed_total 16174
telemt_desync_frames_bucket_total{bucket="1_2"} 5131
telemt_desync_frames_bucket_total{bucket="3_10"} 9547
telemt_desync_frames_bucket_total{bucket="gt_10"} 9527
telemt_pool_swap_total 96
telemt_pool_force_close_total 3254
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 530
telemt_me_draining_writers_reap_progress_total 29413
telemt_me_writer_removed_unexpected_total 669
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2506
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27168
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 235
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26159
telemt_me_writer_teardown_success_total{mode="normal"} 29674
telemt_me_writer_teardown_noop_total 29450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59124
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 144.108523
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59124
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 530
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 613
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 5804316
telemt_user_connections_current{user="hello"} 3241
telemt_user_octets_from_client{user="hello"} 99803379276 (92.95 GB)
telemt_user_octets_to_client{user="hello"} 1857540519268 (1.69 TB)
telemt_user_unique_ips_current{user="hello"} 1406
telemt_user_unique_ips_recent_window{user="hello"} 336
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 89977.3 (24h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5799273
telemt_connections_bad_total 569023
telemt_connections_current 2306
telemt_connections_me_current 2306
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 189140
telemt_upstream_connect_attempt_total 36294
telemt_upstream_connect_success_total 35972
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 36140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17247
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1694
telemt_me_reconnect_success_total 717
telemt_me_reader_eof_total 693
telemt_me_idle_close_by_peer_total 693
telemt_me_route_drop_no_conn_total 2011556
telemt_me_route_drop_channel_closed_total 228
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4325372
telemt_me_endpoint_quarantine_total 544
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 684
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_me_writers_active_current 46
telemt_desync_total 20825
telemt_desync_full_logged_total 6932
telemt_desync_suppressed_total 13893
telemt_desync_frames_bucket_total{bucket="1_2"} 5065
telemt_desync_frames_bucket_total{bucket="3_10"} 8055
telemt_desync_frames_bucket_total{bucket="gt_10"} 7705
telemt_pool_swap_total 98
telemt_pool_force_close_total 2980
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 334
telemt_me_draining_writers_reap_progress_total 28062
telemt_me_writer_removed_unexpected_total 670
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2423
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26240
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2781
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25082
telemt_me_writer_teardown_success_total{mode="normal"} 28663
telemt_me_writer_teardown_noop_total 28067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56730
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.717613
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56730
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 334
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 617
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 4308529
telemt_user_connections_current{user="hello"} 2306
telemt_user_octets_from_client{user="hello"} 132649124633 (123.54 GB)
telemt_user_octets_to_client{user="hello"} 1997107688071 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1002
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 89941.9 (24h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5722881
telemt_connections_bad_total 524264
telemt_connections_current 2424
telemt_connections_me_current 2424
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 176229
telemt_upstream_connect_attempt_total 42718
telemt_upstream_connect_success_total 42439
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 42574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1042
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1747
telemt_me_reconnect_success_total 781
telemt_me_reader_eof_total 726
telemt_me_idle_close_by_peer_total 726
telemt_me_route_drop_no_conn_total 2043167
telemt_me_route_drop_channel_closed_total 107
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4301293
telemt_me_endpoint_quarantine_total 601
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 668
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
telemt_me_writers_active_current 46
telemt_desync_total 20581
telemt_desync_full_logged_total 6758
telemt_desync_suppressed_total 13823
telemt_desync_frames_bucket_total{bucket="1_2"} 5120
telemt_desync_frames_bucket_total{bucket="3_10"} 7807
telemt_desync_frames_bucket_total{bucket="gt_10"} 7654
telemt_pool_swap_total 96
telemt_pool_force_close_total 2852
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 346
telemt_me_draining_writers_reap_progress_total 29494
telemt_me_writer_removed_unexpected_total 695
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2517
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27676
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2639
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26642
telemt_me_writer_teardown_success_total{mode="normal"} 30193
telemt_me_writer_teardown_noop_total 29504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59697
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.672534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59697
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 346
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 675
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 4303162
telemt_user_connections_current{user="hello"} 2424
telemt_user_octets_from_client{user="hello"} 126835524271 (118.12 GB)
telemt_user_octets_to_client{user="hello"} 1965714544983 (1.79 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1025
telemt_user_unique_ips_recent_window{user="hello"} 280
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 89980.6 (24h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19455497
telemt_connections_bad_total 1314039
telemt_connections_current 2997
telemt_connections_me_current 2997
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 546788
telemt_upstream_connect_attempt_total 182322
telemt_upstream_connect_success_total 165042
telemt_upstream_connect_fail_total 15812
telemt_upstream_connect_attempts_per_request{bucket="1"} 180854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8853
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15812
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59676
telemt_me_reconnect_success_total 1931
telemt_me_reader_eof_total 1274
telemt_me_idle_close_by_peer_total 1273
telemt_me_route_drop_no_conn_total 39355550
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15956839
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 656
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 698
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
telemt_me_writers_active_current 49
telemt_desync_total 30239
telemt_desync_full_logged_total 8928
telemt_desync_suppressed_total 21311
telemt_desync_frames_bucket_total{bucket="1_2"} 6627
telemt_desync_frames_bucket_total{bucket="3_10"} 13409
telemt_desync_frames_bucket_total{bucket="gt_10"} 10203
telemt_pool_swap_total 91
telemt_pool_force_close_total 3070
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 700
telemt_me_draining_writers_reap_progress_total 27702
telemt_me_writer_removed_unexpected_total 1812
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3772
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25486
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2570
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 500
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24632
telemt_me_writer_teardown_success_total{mode="normal"} 29258
telemt_me_writer_teardown_noop_total 27728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56986
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 205.188556
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56986
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 700
telemt_me_refill_failed_total 3519
telemt_me_writer_restored_same_endpoint_total 1352
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14245
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 16081868
telemt_user_connections_current{user="hello"} 2998
telemt_user_octets_from_client{user="hello"} 163688107254 (152.45 GB)
telemt_user_octets_to_client{user="hello"} 1009308318674 (939.99 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1298
telemt_user_unique_ips_recent_window{user="hello"} 366
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 89948.0 (24h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5575160
telemt_connections_bad_total 528172
telemt_connections_current 2447
telemt_connections_me_current 2447
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 115074
telemt_upstream_connect_attempt_total 45860
telemt_upstream_connect_success_total 45358
telemt_upstream_connect_fail_total 417
telemt_upstream_connect_attempts_per_request{bucket="1"} 45775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18974
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 417
telemt_me_reconnect_attempts_total 11127
telemt_me_reconnect_success_total 1290
telemt_me_reader_eof_total 1219
telemt_me_idle_close_by_peer_total 1219
telemt_me_route_drop_no_conn_total 2305797
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4338734
telemt_me_endpoint_quarantine_total 546
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 668
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
telemt_desync_total 21719
telemt_desync_full_logged_total 7540
telemt_desync_suppressed_total 14179
telemt_desync_frames_bucket_total{bucket="1_2"} 4144
telemt_desync_frames_bucket_total{bucket="3_10"} 8432
telemt_desync_frames_bucket_total{bucket="gt_10"} 9143
telemt_pool_swap_total 91
telemt_pool_force_close_total 2703
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 340
telemt_me_draining_writers_reap_progress_total 30328
telemt_me_writer_removed_unexpected_total 1198
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3072
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28468
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2335
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27625
telemt_me_writer_teardown_success_total{mode="normal"} 31540
telemt_me_writer_teardown_noop_total 30329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61869
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.577764
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61869
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 340
telemt_me_refill_failed_total 593
telemt_me_writer_restored_same_endpoint_total 1090
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 1512
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4328215
telemt_user_connections_current{user="hello"} 2447
telemt_user_octets_from_client{user="hello"} 115491984169 (107.56 GB)
telemt_user_octets_to_client{user="hello"} 1760165281935 (1.60 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1105
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 26783.8 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3347420
telemt_connections_bad_total 122023
telemt_connections_current 2144
telemt_connections_me_current 2144
telemt_handshake_timeouts_total 1411039
telemt_upstream_connect_attempt_total 8819
telemt_upstream_connect_success_total 8706
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 8813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4775
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 2260
telemt_me_reconnect_success_total 284
telemt_me_reader_eof_total 226
telemt_me_idle_close_by_peer_total 226
telemt_me_route_drop_no_conn_total 949906
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1601059
telemt_me_endpoint_quarantine_total 129
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 198
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 8922
telemt_desync_full_logged_total 2977
telemt_desync_suppressed_total 5945
telemt_desync_frames_bucket_total{bucket="1_2"} 1604
telemt_desync_frames_bucket_total{bucket="3_10"} 3413
telemt_desync_frames_bucket_total{bucket="gt_10"} 3905
telemt_pool_swap_total 28
telemt_pool_force_close_total 905
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 7684
telemt_me_writer_removed_unexpected_total 243
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 705
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7230
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 793
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6779
telemt_me_writer_teardown_success_total{mode="normal"} 7935
telemt_me_writer_teardown_noop_total 7685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15620
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.358629
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15620
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 231
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1596526
telemt_user_connections_current{user="hello"} 2144
telemt_user_octets_from_client{user="hello"} 46538071040 (43.34 GB)
telemt_user_octets_to_client{user="hello"} 678842499544 (632.22 GB)
telemt_user_unique_ips_current{user="hello"} 929
telemt_user_unique_ips_recent_window{user="hello"} 285
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 7754.7 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104854
telemt_connections_bad_total 1201
telemt_connections_current 548
telemt_connections_me_current 548
telemt_handshake_timeouts_total 3079
telemt_upstream_connect_attempt_total 3311
telemt_upstream_connect_success_total 3302
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 3310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 70
telemt_me_reconnect_success_total 39
telemt_me_reader_eof_total 39
telemt_me_idle_close_by_peer_total 39
telemt_me_route_drop_no_conn_total 29166
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89717
telemt_me_endpoint_quarantine_total 55
telemt_me_single_endpoint_shadow_rotate_total 69
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
telemt_me_writers_active_current 45
telemt_desync_total 839
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 641
telemt_desync_frames_bucket_total{bucket="1_2"} 364
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 8
telemt_pool_force_close_total 217
telemt_me_writer_close_signal_drop_total 11
telemt_me_draining_writers_reap_progress_total 2881
telemt_me_writer_removed_unexpected_total 39
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 194
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2726
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2664
telemt_me_writer_teardown_success_total{mode="normal"} 2920
telemt_me_writer_teardown_noop_total 2881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5801
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.501013
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5801
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 11
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 89579
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 2087542024 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 59489038976 (55.40 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 89952.5 (24h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6637443
telemt_connections_bad_total 671029
telemt_connections_current 2841
telemt_connections_me_current 2841
telemt_handshake_timeouts_total 191610
telemt_upstream_connect_attempt_total 33998
telemt_upstream_connect_success_total 33862
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 33961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17041
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_reconnect_attempts_total 1415
telemt_me_reconnect_success_total 719
telemt_me_reader_eof_total 695
telemt_me_idle_close_by_peer_total 695
telemt_me_route_drop_no_conn_total 2037223
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5081136
telemt_me_endpoint_quarantine_total 593
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 683
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
telemt_me_writers_active_current 45
telemt_desync_total 19487
telemt_desync_full_logged_total 6496
telemt_desync_suppressed_total 12991
telemt_desync_frames_bucket_total{bucket="1_2"} 4746
telemt_desync_frames_bucket_total{bucket="3_10"} 7124
telemt_desync_frames_bucket_total{bucket="gt_10"} 7617
telemt_pool_swap_total 99
telemt_pool_force_close_total 2711
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 341
telemt_me_draining_writers_reap_progress_total 30532
telemt_me_writer_removed_unexpected_total 676
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2479
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28738
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2626
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27821
telemt_me_writer_teardown_success_total{mode="normal"} 31217
telemt_me_writer_teardown_noop_total 30534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61751
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.121167
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61751
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 341
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 643
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 5056812
telemt_user_connections_current{user="hello"} 2841
telemt_user_octets_from_client{user="hello"} 101719617220 (94.73 GB)
telemt_user_octets_to_client{user="hello"} 2370459794372 (2.16 TB)
telemt_user_unique_ips_current{user="hello"} 1044
telemt_user_unique_ips_recent_window{user="hello"} 285
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 89949.2 (24h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5651332
telemt_connections_bad_total 533941
telemt_connections_current 2711
telemt_connections_me_current 2711
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 161062
telemt_upstream_connect_attempt_total 50251
telemt_upstream_connect_success_total 49877
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 50192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18879
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_reconnect_attempts_total 4585
telemt_me_reconnect_success_total 1006
telemt_me_reader_eof_total 895
telemt_me_idle_close_by_peer_total 895
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2093183
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4448392
telemt_me_endpoint_quarantine_total 704
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 682
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
telemt_me_writers_active_current 44
telemt_desync_total 18073
telemt_desync_full_logged_total 6106
telemt_desync_suppressed_total 11967
telemt_desync_frames_bucket_total{bucket="1_2"} 4461
telemt_desync_frames_bucket_total{bucket="3_10"} 6619
telemt_desync_frames_bucket_total{bucket="gt_10"} 6993
telemt_pool_swap_total 97
telemt_pool_force_close_total 2648
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 340
telemt_me_draining_writers_reap_progress_total 29618
telemt_me_writer_removed_unexpected_total 906
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2954
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27612
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2444
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 204
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26970
telemt_me_writer_teardown_success_total{mode="normal"} 30566
telemt_me_writer_teardown_noop_total 29622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60188
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.057484
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60188
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 340
telemt_me_refill_failed_total 204
telemt_me_writer_restored_same_endpoint_total 775
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 4452249
telemt_user_connections_current{user="hello"} 2711
telemt_user_octets_from_client{user="hello"} 84757173113 (78.94 GB)
telemt_user_octets_to_client{user="hello"} 1889643531464 (1.72 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1146
telemt_user_unique_ips_recent_window{user="hello"} 313
```