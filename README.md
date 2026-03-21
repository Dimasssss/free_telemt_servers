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

# Server Metrics 2026-03-21 14:16:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 63663.0 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2186270
telemt_connections_bad_total 107246
telemt_connections_current 1522
telemt_connections_me_current 1522
telemt_handshake_timeouts_total 74847
telemt_upstream_connect_attempt_total 24441
telemt_upstream_connect_success_total 24317
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 24398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15638
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1438
telemt_me_reconnect_success_total 607
telemt_me_reader_eof_total 582
telemt_me_idle_close_by_peer_total 582
telemt_me_route_drop_no_conn_total 1872101
telemt_me_route_drop_channel_closed_total 581
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1743837
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 444
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 500
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
telemt_me_writers_active_current 89
telemt_desync_total 6870
telemt_desync_full_logged_total 2343
telemt_desync_suppressed_total 4527
telemt_desync_frames_bucket_total{bucket="1_2"} 1530
telemt_desync_frames_bucket_total{bucket="3_10"} 2624
telemt_desync_frames_bucket_total{bucket="gt_10"} 2716
telemt_pool_swap_total 68
telemt_pool_force_close_total 2060
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 431
telemt_me_draining_writers_reap_progress_total 21815
telemt_me_writer_removed_unexpected_total 564
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1830
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20339
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1983
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19755
telemt_me_writer_teardown_success_total{mode="normal"} 22169
telemt_me_writer_teardown_noop_total 21821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43990
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 195.680940
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43990
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 431
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 531
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1742510
telemt_user_connections_current{user="hello"} 1522
telemt_user_octets_from_client{user="hello"} 25264946299 (23.53 GB)
telemt_user_octets_to_client{user="hello"} 435623047099 (405.71 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 3216.4 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273310
telemt_connections_bad_total 9944
telemt_connections_current 2854
telemt_connections_me_current 2854
telemt_handshake_timeouts_total 8355
telemt_upstream_connect_attempt_total 1255
telemt_upstream_connect_success_total 1253
telemt_upstream_connect_attempts_per_request{bucket="1"} 1253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 104
telemt_me_reconnect_success_total 20
telemt_me_reader_eof_total 18
telemt_me_idle_close_by_peer_total 18
telemt_me_route_drop_no_conn_total 167565
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 241995
telemt_me_endpoint_quarantine_total 24
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
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
telemt_me_writers_active_current 43
telemt_desync_total 991
telemt_desync_full_logged_total 396
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 205
telemt_desync_frames_bucket_total{bucket="3_10"} 385
telemt_desync_frames_bucket_total{bucket="gt_10"} 401
telemt_pool_swap_total 3
telemt_pool_force_close_total 80
telemt_me_writer_close_signal_drop_total 19
telemt_me_draining_writers_reap_progress_total 865
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 820
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 785
telemt_me_writer_teardown_success_total{mode="normal"} 883
telemt_me_writer_teardown_noop_total 865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1748
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.307494
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1748
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 19
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 238024
telemt_user_connections_current{user="hello"} 2854
telemt_user_octets_from_client{user="hello"} 4292976627 (4.00 GB)
telemt_user_octets_to_client{user="hello"} 57875864891 (53.90 GB)
telemt_user_msgs_from_client{user="hello"} 423
telemt_user_msgs_to_client{user="hello"} 734
telemt_user_unique_ips_current{user="hello"} 1398
telemt_user_unique_ips_recent_window{user="hello"} 458
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 63660.8 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4303911
telemt_connections_bad_total 403183
telemt_connections_current 4271
telemt_connections_me_current 4271
telemt_handshake_timeouts_total 162633
telemt_upstream_connect_attempt_total 24017
telemt_upstream_connect_success_total 23973
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 953
telemt_me_reconnect_success_total 549
telemt_me_reader_eof_total 548
telemt_me_idle_close_by_peer_total 548
telemt_me_route_drop_no_conn_total 2334587
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3493904
telemt_me_endpoint_quarantine_total 402
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 485
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
telemt_desync_total 14526
telemt_desync_full_logged_total 4907
telemt_desync_suppressed_total 9619
telemt_desync_frames_bucket_total{bucket="1_2"} 3091
telemt_desync_frames_bucket_total{bucket="3_10"} 5715
telemt_desync_frames_bucket_total{bucket="gt_10"} 5720
telemt_pool_swap_total 67
telemt_pool_force_close_total 2162
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 337
telemt_me_draining_writers_reap_progress_total 21797
telemt_me_writer_removed_unexpected_total 529
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1899
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20218
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1974
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19635
telemt_me_writer_teardown_success_total{mode="normal"} 22117
telemt_me_writer_teardown_noop_total 21826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43943
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 70.247486
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43943
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 337
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 499
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 3489560
telemt_user_connections_current{user="hello"} 4271
telemt_user_octets_from_client{user="hello"} 56916330164 (53.01 GB)
telemt_user_octets_to_client{user="hello"} 1179337123300 (1.07 TB)
telemt_user_unique_ips_current{user="hello"} 1695
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 63662.7 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3508677
telemt_connections_bad_total 389829
telemt_connections_current 3843
telemt_connections_me_current 3843
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 129875
telemt_upstream_connect_attempt_total 28317
telemt_upstream_connect_success_total 28039
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 28175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12997
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 480
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1183
telemt_me_reconnect_success_total 551
telemt_me_reader_eof_total 518
telemt_me_idle_close_by_peer_total 518
telemt_me_route_drop_no_conn_total 1094042
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2545869
telemt_me_endpoint_quarantine_total 411
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 486
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
telemt_desync_total 11655
telemt_desync_full_logged_total 3950
telemt_desync_suppressed_total 7705
telemt_desync_frames_bucket_total{bucket="1_2"} 2926
telemt_desync_frames_bucket_total{bucket="3_10"} 4496
telemt_desync_frames_bucket_total{bucket="gt_10"} 4233
telemt_pool_swap_total 69
telemt_pool_force_close_total 1975
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 182
telemt_me_draining_writers_reap_progress_total 20941
telemt_me_writer_removed_unexpected_total 502
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1768
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19682
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1842
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 133
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18966
telemt_me_writer_teardown_success_total{mode="normal"} 21450
telemt_me_writer_teardown_noop_total 20942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42392
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.137696
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42392
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 182
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 465
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 2546125
telemt_user_connections_current{user="hello"} 3843
telemt_user_octets_from_client{user="hello"} 47491798589 (44.23 GB)
telemt_user_octets_to_client{user="hello"} 1190467837503 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1490
telemt_user_unique_ips_recent_window{user="hello"} 511
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 63625.9 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3410492
telemt_connections_bad_total 362692
telemt_connections_current 3422
telemt_connections_me_current 3422
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 100242
telemt_upstream_connect_attempt_total 33528
telemt_upstream_connect_success_total 33297
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 33430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 847
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1288
telemt_me_reconnect_success_total 627
telemt_me_reader_eof_total 571
telemt_me_idle_close_by_peer_total 571
telemt_me_route_drop_no_conn_total 1048372
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2503105
telemt_me_endpoint_quarantine_total 463
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 477
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
telemt_me_writers_active_current 46
telemt_desync_total 11712
telemt_desync_full_logged_total 3902
telemt_desync_suppressed_total 7810
telemt_desync_frames_bucket_total{bucket="1_2"} 2959
telemt_desync_frames_bucket_total{bucket="3_10"} 4404
telemt_desync_frames_bucket_total{bucket="gt_10"} 4349
telemt_pool_swap_total 67
telemt_pool_force_close_total 1908
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 218
telemt_me_draining_writers_reap_progress_total 22298
telemt_me_writer_removed_unexpected_total 544
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1878
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20999
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1736
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 172
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20390
telemt_me_writer_teardown_success_total{mode="normal"} 22877
telemt_me_writer_teardown_noop_total 22303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45180
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.605304
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45180
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 218
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 546
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2507390
telemt_user_connections_current{user="hello"} 3422
telemt_user_octets_from_client{user="hello"} 54172218269 (50.45 GB)
telemt_user_octets_to_client{user="hello"} 1182882889308 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1403
telemt_user_unique_ips_recent_window{user="hello"} 540
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 63665.2 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11684399
telemt_connections_bad_total 776992
telemt_connections_current 4860
telemt_connections_me_current 4860
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 363929
telemt_upstream_connect_attempt_total 114680
telemt_upstream_connect_success_total 104830
telemt_upstream_connect_fail_total 8841
telemt_upstream_connect_attempts_per_request{bucket="1"} 113671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24871
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8841
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3817
telemt_me_reconnect_success_total 1358
telemt_me_reader_eof_total 945
telemt_me_idle_close_by_peer_total 944
telemt_me_route_drop_no_conn_total 21676827
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9572793
telemt_me_endpoint_quarantine_total 494
telemt_me_single_endpoint_outage_enter_total 77
telemt_me_single_endpoint_outage_exit_total 77
telemt_me_single_endpoint_outage_reconnect_attempt_total 173
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 173
telemt_me_single_endpoint_shadow_rotate_total 502
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
telemt_me_writers_active_current 45
telemt_desync_total 17528
telemt_desync_full_logged_total 5558
telemt_desync_suppressed_total 11970
telemt_desync_frames_bucket_total{bucket="1_2"} 3823
telemt_desync_frames_bucket_total{bucket="3_10"} 7662
telemt_desync_frames_bucket_total{bucket="gt_10"} 6043
telemt_pool_swap_total 64
telemt_pool_force_close_total 2067
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 447
telemt_me_draining_writers_reap_progress_total 20620
telemt_me_writer_removed_unexpected_total 1306
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2755
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18992
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1723
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 344
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18553
telemt_me_writer_teardown_success_total{mode="normal"} 21747
telemt_me_writer_teardown_noop_total 20630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42377
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 163.439562
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42377
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 447
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 942
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 355
telemt_user_connections_total{user="hello"} 9649156
telemt_user_connections_current{user="hello"} 4860
telemt_user_octets_from_client{user="hello"} 70796446193 (65.93 GB)
telemt_user_octets_to_client{user="hello"} 754607669857 (702.78 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 1773
telemt_user_unique_ips_recent_window{user="hello"} 1022
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 63632.9 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3432680
telemt_connections_bad_total 384950
telemt_connections_current 4315
telemt_connections_me_current 4315
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 75419
telemt_upstream_connect_attempt_total 27226
telemt_upstream_connect_success_total 26934
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 27192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_reconnect_attempts_total 2645
telemt_me_reconnect_success_total 960
telemt_me_reader_eof_total 953
telemt_me_idle_close_by_peer_total 953
telemt_me_route_drop_no_conn_total 1376013
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2632487
telemt_me_endpoint_quarantine_total 401
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 479
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
telemt_me_writers_active_current 45
telemt_desync_total 12489
telemt_desync_full_logged_total 4341
telemt_desync_suppressed_total 8148
telemt_desync_frames_bucket_total{bucket="1_2"} 2413
telemt_desync_frames_bucket_total{bucket="3_10"} 4977
telemt_desync_frames_bucket_total{bucket="gt_10"} 5099
telemt_pool_swap_total 63
telemt_pool_force_close_total 1827
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 177
telemt_me_draining_writers_reap_progress_total 22805
telemt_me_writer_removed_unexpected_total 924
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2241
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21518
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1583
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 244
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20978
telemt_me_writer_teardown_success_total{mode="normal"} 23759
telemt_me_writer_teardown_noop_total 22806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46565
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.128286
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46565
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 177
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 821
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 2616475
telemt_user_connections_current{user="hello"} 4315
telemt_user_octets_from_client{user="hello"} 57753981832 (53.79 GB)
telemt_user_octets_to_client{user="hello"} 1121084409266 (1.02 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1647
telemt_user_unique_ips_recent_window{user="hello"} 564
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 468.4 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81109
telemt_connections_bad_total 1626
telemt_connections_current 3318
telemt_connections_me_current 3318
telemt_handshake_timeouts_total 42797
telemt_upstream_connect_attempt_total 205
telemt_upstream_connect_success_total 198
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 95
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 15043
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32126
telemt_me_endpoint_quarantine_total 1
telemt_me_single_endpoint_shadow_rotate_total 7
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
telemt_me_writers_active_current 46
telemt_desync_total 137
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 111
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 111
telemt_me_writer_teardown_success_total{mode="normal"} 111
telemt_me_writer_teardown_noop_total 111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 222
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.000764
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 222
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_user_connections_total{user="hello"} 32124
telemt_user_connections_current{user="hello"} 3318
telemt_user_octets_from_client{user="hello"} 429913956 (410.00 MB)
telemt_user_octets_to_client{user="hello"} 12045294728 (11.22 GB)
telemt_user_unique_ips_current{user="hello"} 1285
telemt_user_unique_ips_recent_window{user="hello"} 570
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 61618.6 (17h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1121560
telemt_connections_bad_total 135678
telemt_connections_current 774
telemt_connections_me_current 774
telemt_handshake_timeouts_total 396827
telemt_upstream_connect_attempt_total 28838
telemt_upstream_connect_success_total 28835
telemt_upstream_connect_attempts_per_request{bucket="1"} 28835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1223
telemt_me_reconnect_success_total 475
telemt_me_reader_eof_total 473
telemt_me_idle_close_by_peer_total 473
telemt_me_route_drop_no_conn_total 237798
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 517717
telemt_me_endpoint_quarantine_total 562
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 520
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 3341
telemt_desync_full_logged_total 1234
telemt_desync_suppressed_total 2107
telemt_desync_frames_bucket_total{bucket="1_2"} 601
telemt_desync_frames_bucket_total{bucket="3_10"} 1195
telemt_desync_frames_bucket_total{bucket="gt_10"} 1545
telemt_pool_swap_total 68
telemt_pool_force_close_total 1553
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 108
telemt_me_draining_writers_reap_progress_total 25858
telemt_me_writer_removed_unexpected_total 446
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1894
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24422
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1550
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24305
telemt_me_writer_teardown_success_total{mode="normal"} 26316
telemt_me_writer_teardown_noop_total 25858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52174
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.540431
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52174
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 108
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 386
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 517459
telemt_user_connections_current{user="hello"} 774
telemt_user_octets_from_client{user="hello"} 10624133975 (9.89 GB)
telemt_user_octets_to_client{user="hello"} 194885480713 (181.50 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 63637.2 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3756016
telemt_connections_bad_total 348370
telemt_connections_current 4746
telemt_connections_me_current 4746
telemt_handshake_timeouts_total 117319
telemt_upstream_connect_attempt_total 25735
telemt_upstream_connect_success_total 25631
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 25703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12847
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1048
telemt_me_reconnect_success_total 584
telemt_me_reader_eof_total 546
telemt_me_idle_close_by_peer_total 546
telemt_me_route_drop_no_conn_total 1121638
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2978198
telemt_me_endpoint_quarantine_total 471
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 489
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
telemt_me_writers_active_current 42
telemt_desync_total 11789
telemt_desync_full_logged_total 3900
telemt_desync_suppressed_total 7889
telemt_desync_frames_bucket_total{bucket="1_2"} 2803
telemt_desync_frames_bucket_total{bucket="3_10"} 4390
telemt_desync_frames_bucket_total{bucket="gt_10"} 4596
telemt_pool_swap_total 70
telemt_pool_force_close_total 1820
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 198
telemt_me_draining_writers_reap_progress_total 23125
telemt_me_writer_removed_unexpected_total 535
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1816
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21844
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1784
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21305
telemt_me_writer_teardown_success_total{mode="normal"} 23660
telemt_me_writer_teardown_noop_total 23125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46785
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.274611
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46785
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 198
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 516
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 2970356
telemt_user_connections_current{user="hello"} 4746
telemt_user_octets_from_client{user="hello"} 62051407364 (57.79 GB)
telemt_user_octets_to_client{user="hello"} 1400598613036 (1.27 TB)
telemt_user_unique_ips_current{user="hello"} 1680
telemt_user_unique_ips_recent_window{user="hello"} 620
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 63633.9 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3373374
telemt_connections_bad_total 296226
telemt_connections_current 3723
telemt_connections_me_current 3723
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 98220
telemt_upstream_connect_attempt_total 41950
telemt_upstream_connect_success_total 41672
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 41901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14557
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 591
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_reconnect_attempts_total 3579
telemt_me_reconnect_success_total 759
telemt_me_reader_eof_total 666
telemt_me_idle_close_by_peer_total 666
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1202318
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2711547
telemt_me_endpoint_quarantine_total 535
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 487
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
telemt_me_writers_active_current 45
telemt_desync_total 10450
telemt_desync_full_logged_total 3558
telemt_desync_suppressed_total 6892
telemt_desync_frames_bucket_total{bucket="1_2"} 2631
telemt_desync_frames_bucket_total{bucket="3_10"} 3862
telemt_desync_frames_bucket_total{bucket="gt_10"} 3957
telemt_pool_swap_total 69
telemt_pool_force_close_total 1769
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 22285
telemt_me_writer_removed_unexpected_total 678
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2129
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20865
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1648
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20516
telemt_me_writer_teardown_success_total{mode="normal"} 22994
telemt_me_writer_teardown_noop_total 22286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45280
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.458305
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45280
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 579
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 2720474
telemt_user_connections_current{user="hello"} 3723
telemt_user_octets_from_client{user="hello"} 49159838197 (45.78 GB)
telemt_user_octets_to_client{user="hello"} 1170550855492 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1441
telemt_user_unique_ips_recent_window{user="hello"} 517
```