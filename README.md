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

# Server Metrics 2026-03-21 14:42:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 65186.4 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2258905
telemt_connections_bad_total 111536
telemt_connections_current 1482
telemt_connections_me_current 1482
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 75439
telemt_upstream_connect_attempt_total 28095
telemt_upstream_connect_success_total 27970
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1634
telemt_me_reconnect_success_total 647
telemt_me_reader_eof_total 619
telemt_me_idle_close_by_peer_total 619
telemt_me_route_drop_no_conn_total 1900365
telemt_me_route_drop_channel_closed_total 603
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1803162
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 462
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 512
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
telemt_me_writers_active_current 43
telemt_desync_total 7102
telemt_desync_full_logged_total 2435
telemt_desync_suppressed_total 4667
telemt_desync_frames_bucket_total{bucket="1_2"} 1564
telemt_desync_frames_bucket_total{bucket="3_10"} 2708
telemt_desync_frames_bucket_total{bucket="gt_10"} 2830
telemt_pool_swap_total 70
telemt_pool_force_close_total 2123
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 475
telemt_me_draining_writers_reap_progress_total 22394
telemt_me_writer_removed_unexpected_total 599
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1917
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20865
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2010
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 113
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20271
telemt_me_writer_teardown_success_total{mode="normal"} 22782
telemt_me_writer_teardown_noop_total 22400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45182
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 208.400688
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45182
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 475
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 555
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1804809
telemt_user_connections_current{user="hello"} 1482
telemt_user_octets_from_client{user="hello"} 25901777605 (24.12 GB)
telemt_user_octets_to_client{user="hello"} 449041138566 (418.20 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 551
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 4739.8 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359179
telemt_connections_bad_total 12736
telemt_connections_current 1769
telemt_connections_me_current 1769
telemt_handshake_timeouts_total 11879
telemt_upstream_connect_attempt_total 1823
telemt_upstream_connect_success_total 1810
telemt_upstream_connect_attempts_per_request{bucket="1"} 1810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 875
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 130
telemt_me_reconnect_success_total 44
telemt_me_reader_eof_total 37
telemt_me_idle_close_by_peer_total 37
telemt_me_route_drop_no_conn_total 234980
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318530
telemt_me_endpoint_quarantine_total 35
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 42
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
telemt_me_writers_active_current 43
telemt_desync_total 1306
telemt_desync_full_logged_total 548
telemt_desync_suppressed_total 758
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 516
telemt_desync_frames_bucket_total{bucket="gt_10"} 528
telemt_pool_swap_total 5
telemt_pool_force_close_total 142
telemt_me_writer_close_signal_drop_total 25
telemt_me_draining_writers_reap_progress_total 1340
telemt_me_writer_removed_unexpected_total 34
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 111
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1266
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 137
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1198
telemt_me_writer_teardown_success_total{mode="normal"} 1377
telemt_me_writer_teardown_noop_total 1340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2717
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.760426
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2717
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 25
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 311619
telemt_user_connections_current{user="hello"} 1769
telemt_user_octets_from_client{user="hello"} 5365832943 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 81337211131 (75.75 GB)
telemt_user_msgs_from_client{user="hello"} 423
telemt_user_msgs_to_client{user="hello"} 734
telemt_user_unique_ips_current{user="hello"} 1012
telemt_user_unique_ips_recent_window{user="hello"} 560
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 65184.2 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4460233
telemt_connections_bad_total 407959
telemt_connections_current 4090
telemt_connections_me_current 4090
telemt_handshake_timeouts_total 166146
telemt_upstream_connect_attempt_total 24443
telemt_upstream_connect_success_total 24392
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 24397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1073
telemt_me_reconnect_success_total 565
telemt_me_reader_eof_total 565
telemt_me_idle_close_by_peer_total 565
telemt_me_route_drop_no_conn_total 2434381
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3632932
telemt_me_endpoint_quarantine_total 419
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 495
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
telemt_me_writers_active_current 40
telemt_desync_total 15049
telemt_desync_full_logged_total 5074
telemt_desync_suppressed_total 9975
telemt_desync_frames_bucket_total{bucket="1_2"} 3191
telemt_desync_frames_bucket_total{bucket="3_10"} 5936
telemt_desync_frames_bucket_total{bucket="gt_10"} 5922
telemt_pool_swap_total 69
telemt_pool_force_close_total 2235
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 349
telemt_me_draining_writers_reap_progress_total 22183
telemt_me_writer_removed_unexpected_total 546
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1942
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20569
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2042
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 193
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19948
telemt_me_writer_teardown_success_total{mode="normal"} 22511
telemt_me_writer_teardown_noop_total 22214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44725
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 73.354188
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44725
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 349
telemt_me_refill_failed_total 26
telemt_me_writer_restored_same_endpoint_total 507
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 3628404
telemt_user_connections_current{user="hello"} 4090
telemt_user_octets_from_client{user="hello"} 59165912288 (55.10 GB)
telemt_user_octets_to_client{user="hello"} 1219932888220 (1.11 TB)
telemt_user_unique_ips_current{user="hello"} 1589
telemt_user_unique_ips_recent_window{user="hello"} 644
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 65185.3 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3647297
telemt_connections_bad_total 402688
telemt_connections_current 4069
telemt_connections_me_current 4069
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 133671
telemt_upstream_connect_attempt_total 28806
telemt_upstream_connect_success_total 28527
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13271
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 483
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1196
telemt_me_reconnect_success_total 562
telemt_me_reader_eof_total 530
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 1133338
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2652135
telemt_me_endpoint_quarantine_total 423
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 499
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
telemt_me_writers_active_current 44
telemt_desync_total 12297
telemt_desync_full_logged_total 4142
telemt_desync_suppressed_total 8155
telemt_desync_frames_bucket_total{bucket="1_2"} 3101
telemt_desync_frames_bucket_total{bucket="3_10"} 4740
telemt_desync_frames_bucket_total{bucket="gt_10"} 4456
telemt_pool_swap_total 71
telemt_pool_force_close_total 2042
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 192
telemt_me_draining_writers_reap_progress_total 21359
telemt_me_writer_removed_unexpected_total 514
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1807
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20068
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1907
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 135
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19317
telemt_me_writer_teardown_success_total{mode="normal"} 21875
telemt_me_writer_teardown_noop_total 21360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43235
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.216274
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43235
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 192
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 475
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2652201
telemt_user_connections_current{user="hello"} 4069
telemt_user_octets_from_client{user="hello"} 49569827937 (46.17 GB)
telemt_user_octets_to_client{user="hello"} 1237986357107 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1522
telemt_user_unique_ips_recent_window{user="hello"} 528
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 65149.4 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3551675
telemt_connections_bad_total 381505
telemt_connections_current 3275
telemt_connections_me_current 3275
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 105485
telemt_upstream_connect_attempt_total 34027
telemt_upstream_connect_success_total 33795
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 33928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14655
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 849
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1307
telemt_me_reconnect_success_total 635
telemt_me_reader_eof_total 577
telemt_me_idle_close_by_peer_total 577
telemt_me_route_drop_no_conn_total 1096270
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2609340
telemt_me_endpoint_quarantine_total 472
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 491
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
telemt_me_writers_active_current 44
telemt_desync_total 12189
telemt_desync_full_logged_total 4069
telemt_desync_suppressed_total 8120
telemt_desync_frames_bucket_total{bucket="1_2"} 3063
telemt_desync_frames_bucket_total{bucket="3_10"} 4582
telemt_desync_frames_bucket_total{bucket="gt_10"} 4544
telemt_pool_swap_total 69
telemt_pool_force_close_total 1972
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 221
telemt_me_draining_writers_reap_progress_total 22753
telemt_me_writer_removed_unexpected_total 550
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1920
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21418
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 176
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20781
telemt_me_writer_teardown_success_total{mode="normal"} 23338
telemt_me_writer_teardown_noop_total 22758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46096
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.773533
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46096
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 221
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 552
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2613455
telemt_user_connections_current{user="hello"} 3275
telemt_user_octets_from_client{user="hello"} 56563487641 (52.68 GB)
telemt_user_octets_to_client{user="hello"} 1227555658876 (1.12 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1286
telemt_user_unique_ips_recent_window{user="hello"} 502
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 65188.5 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12153575
telemt_connections_bad_total 803368
telemt_connections_current 5362
telemt_connections_me_current 5362
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 376456
telemt_upstream_connect_attempt_total 115198
telemt_upstream_connect_success_total 105335
telemt_upstream_connect_fail_total 8845
telemt_upstream_connect_attempts_per_request{bucket="1"} 114180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8845
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 3834
telemt_me_reconnect_success_total 1372
telemt_me_reader_eof_total 959
telemt_me_idle_close_by_peer_total 958
telemt_me_route_drop_no_conn_total 22767777
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9967275
telemt_me_endpoint_quarantine_total 507
telemt_me_single_endpoint_outage_enter_total 77
telemt_me_single_endpoint_outage_exit_total 77
telemt_me_single_endpoint_outage_reconnect_attempt_total 173
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 173
telemt_me_single_endpoint_shadow_rotate_total 509
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 17969
telemt_desync_full_logged_total 5687
telemt_desync_suppressed_total 12282
telemt_desync_frames_bucket_total{bucket="1_2"} 3936
telemt_desync_frames_bucket_total{bucket="3_10"} 7846
telemt_desync_frames_bucket_total{bucket="gt_10"} 6187
telemt_pool_swap_total 66
telemt_pool_force_close_total 2145
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 461
telemt_me_draining_writers_reap_progress_total 21079
telemt_me_writer_removed_unexpected_total 1320
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2803
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19393
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 349
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18934
telemt_me_writer_teardown_success_total{mode="normal"} 22196
telemt_me_writer_teardown_noop_total 21089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43285
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 167.119548
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43285
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 461
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 955
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 10043436
telemt_user_connections_current{user="hello"} 5362
telemt_user_octets_from_client{user="hello"} 72837917933 (67.84 GB)
telemt_user_octets_to_client{user="hello"} 771935772401 (718.92 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 1920
telemt_user_unique_ips_recent_window{user="hello"} 1048
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 65156.2 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3582752
telemt_connections_bad_total 406968
telemt_connections_current 3944
telemt_connections_me_current 3944
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 78840
telemt_upstream_connect_attempt_total 27694
telemt_upstream_connect_success_total 27389
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 27650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_reconnect_attempts_total 2666
telemt_me_reconnect_success_total 964
telemt_me_reader_eof_total 957
telemt_me_idle_close_by_peer_total 957
telemt_me_route_drop_no_conn_total 1479412
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2746621
telemt_me_endpoint_quarantine_total 409
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 492
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 13116
telemt_desync_full_logged_total 4557
telemt_desync_suppressed_total 8559
telemt_desync_frames_bucket_total{bucket="1_2"} 2533
telemt_desync_frames_bucket_total{bucket="3_10"} 5220
telemt_desync_frames_bucket_total{bucket="gt_10"} 5363
telemt_pool_swap_total 65
telemt_pool_force_close_total 1890
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 186
telemt_me_draining_writers_reap_progress_total 23218
telemt_me_writer_removed_unexpected_total 929
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2280
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21897
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1637
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 253
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21328
telemt_me_writer_teardown_success_total{mode="normal"} 24177
telemt_me_writer_teardown_noop_total 23219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47396
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.252779
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47396
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 186
telemt_me_refill_failed_total 93
telemt_me_writer_restored_same_endpoint_total 825
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 2730390
telemt_user_connections_current{user="hello"} 3944
telemt_user_octets_from_client{user="hello"} 67055647796 (62.45 GB)
telemt_user_octets_to_client{user="hello"} 1154997640326 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1488
telemt_user_unique_ips_recent_window{user="hello"} 541
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 1991.9 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336251
telemt_connections_bad_total 6618
telemt_connections_current 3549
telemt_connections_me_current 3549
telemt_handshake_timeouts_total 174042
telemt_upstream_connect_attempt_total 937
telemt_upstream_connect_success_total 910
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 97
telemt_me_reconnect_success_total 52
telemt_me_reader_eof_total 51
telemt_me_idle_close_by_peer_total 51
telemt_me_route_drop_no_conn_total 138553
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143906
telemt_me_endpoint_quarantine_total 9
telemt_me_single_endpoint_shadow_rotate_total 18
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
telemt_me_writers_active_current 43
telemt_desync_total 589
telemt_desync_full_logged_total 208
telemt_desync_suppressed_total 381
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 693
telemt_me_writer_removed_unexpected_total 52
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 90
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 655
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 666
telemt_me_writer_teardown_success_total{mode="normal"} 745
telemt_me_writer_teardown_noop_total 693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1438
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.219109
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1438
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 143821
telemt_user_connections_current{user="hello"} 3549
telemt_user_octets_from_client{user="hello"} 2316632336 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 53766001688 (50.07 GB)
telemt_user_unique_ips_current{user="hello"} 1401
telemt_user_unique_ips_recent_window{user="hello"} 516
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 63142.3 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1148952
telemt_connections_bad_total 136371
telemt_connections_current 768
telemt_connections_me_current 768
telemt_handshake_timeouts_total 404049
telemt_upstream_connect_attempt_total 29476
telemt_upstream_connect_success_total 29471
telemt_upstream_connect_attempts_per_request{bucket="1"} 29471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1248
telemt_me_reconnect_success_total 482
telemt_me_reader_eof_total 481
telemt_me_idle_close_by_peer_total 481
telemt_me_route_drop_no_conn_total 247484
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536831
telemt_me_endpoint_quarantine_total 575
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 529
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
telemt_desync_total 3431
telemt_desync_full_logged_total 1264
telemt_desync_suppressed_total 2167
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 1227
telemt_desync_frames_bucket_total{bucket="gt_10"} 1583
telemt_pool_swap_total 70
telemt_pool_force_close_total 1578
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 108
telemt_me_draining_writers_reap_progress_total 26406
telemt_me_writer_removed_unexpected_total 454
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1937
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24935
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24828
telemt_me_writer_teardown_success_total{mode="normal"} 26872
telemt_me_writer_teardown_noop_total 26406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53278
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.649989
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53278
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 108
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 393
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 536552
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 11083257591 (10.32 GB)
telemt_user_octets_to_client{user="hello"} 204419348093 (190.38 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 65160.5 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3919331
telemt_connections_bad_total 358499
telemt_connections_current 4434
telemt_connections_me_current 4434
telemt_handshake_timeouts_total 122805
telemt_upstream_connect_attempt_total 26265
telemt_upstream_connect_success_total 26155
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 26231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13107
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 1062
telemt_me_reconnect_success_total 596
telemt_me_reader_eof_total 557
telemt_me_idle_close_by_peer_total 557
telemt_me_route_drop_no_conn_total 1185631
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3115589
telemt_me_endpoint_quarantine_total 483
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 498
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 12229
telemt_desync_full_logged_total 4050
telemt_desync_suppressed_total 8179
telemt_desync_frames_bucket_total{bucket="1_2"} 2889
telemt_desync_frames_bucket_total{bucket="3_10"} 4555
telemt_desync_frames_bucket_total{bucket="gt_10"} 4785
telemt_pool_swap_total 72
telemt_pool_force_close_total 1878
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 209
telemt_me_draining_writers_reap_progress_total 23569
telemt_me_writer_removed_unexpected_total 547
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1864
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22252
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1841
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21691
telemt_me_writer_teardown_success_total{mode="normal"} 24116
telemt_me_writer_teardown_noop_total 23569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47685
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.523970
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47685
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 209
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 527
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 3107522
telemt_user_connections_current{user="hello"} 4434
telemt_user_octets_from_client{user="hello"} 64001604336 (59.61 GB)
telemt_user_octets_to_client{user="hello"} 1465888570776 (1.33 TB)
telemt_user_unique_ips_current{user="hello"} 1526
telemt_user_unique_ips_recent_window{user="hello"} 588
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 65157.2 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3501059
telemt_connections_bad_total 306383
telemt_connections_current 3906
telemt_connections_me_current 3906
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 104332
telemt_upstream_connect_attempt_total 42689
telemt_upstream_connect_success_total 42402
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 42638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14954
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 600
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_reconnect_attempts_total 3626
telemt_me_reconnect_success_total 805
telemt_me_reader_eof_total 711
telemt_me_idle_close_by_peer_total 711
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1260624
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2814606
telemt_me_endpoint_quarantine_total 548
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 498
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
telemt_me_writers_active_current 44
telemt_desync_total 10912
telemt_desync_full_logged_total 3707
telemt_desync_suppressed_total 7205
telemt_desync_frames_bucket_total{bucket="1_2"} 2720
telemt_desync_frames_bucket_total{bucket="3_10"} 4045
telemt_desync_frames_bucket_total{bucket="gt_10"} 4147
telemt_pool_swap_total 70
telemt_pool_force_close_total 1815
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 202
telemt_me_draining_writers_reap_progress_total 22945
telemt_me_writer_removed_unexpected_total 724
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2216
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21484
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1670
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 145
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21130
telemt_me_writer_teardown_success_total{mode="normal"} 23700
telemt_me_writer_teardown_noop_total 22946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46646
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.822257
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46646
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 202
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 625
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 2823417
telemt_user_connections_current{user="hello"} 3906
telemt_user_octets_from_client{user="hello"} 50817925781 (47.33 GB)
telemt_user_octets_to_client{user="hello"} 1214882866448 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1484
telemt_user_unique_ips_recent_window{user="hello"} 551
```