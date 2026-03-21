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

# Server Metrics 2026-03-21 21:30:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 1444.6 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30014
telemt_connections_bad_total 1650
telemt_connections_current 933
telemt_connections_me_current 933
telemt_handshake_timeouts_total 1158
telemt_upstream_connect_attempt_total 579
telemt_upstream_connect_success_total 579
telemt_upstream_connect_attempts_per_request{bucket="1"} 579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 7
telemt_me_idle_close_by_peer_total 7
telemt_me_route_drop_no_conn_total 6447
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25422
telemt_me_endpoint_quarantine_total 12
telemt_me_single_endpoint_shadow_rotate_total 16
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
telemt_desync_total 143
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_close_signal_drop_total 2
telemt_me_draining_writers_reap_progress_total 453
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 433
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 424
telemt_me_writer_teardown_success_total{mode="normal"} 460
telemt_me_writer_teardown_noop_total 453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 913
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.192898
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 913
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 2
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 25409
telemt_user_connections_current{user="hello"} 933
telemt_user_octets_from_client{user="hello"} 246288456 (234.88 MB)
telemt_user_octets_to_client{user="hello"} 7094490200 (6.61 GB)
telemt_user_unique_ips_current{user="hello"} 359
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 14811.4 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 545038
telemt_connections_bad_total 25947
telemt_connections_current 809
telemt_connections_me_current 809
telemt_handshake_timeouts_total 19045
telemt_upstream_connect_attempt_total 5901
telemt_upstream_connect_success_total 5785
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 5888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3217
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_reconnect_attempts_total 499
telemt_me_reconnect_success_total 188
telemt_me_reader_eof_total 165
telemt_me_idle_close_by_peer_total 165
telemt_me_route_drop_no_conn_total 296420
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440014
telemt_me_endpoint_quarantine_total 119
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 119
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
telemt_me_writers_active_current 46
telemt_desync_total 1956
telemt_desync_full_logged_total 1114
telemt_desync_suppressed_total 842
telemt_desync_frames_bucket_total{bucket="1_2"} 399
telemt_desync_frames_bucket_total{bucket="3_10"} 754
telemt_desync_frames_bucket_total{bucket="gt_10"} 803
telemt_pool_swap_total 16
telemt_pool_force_close_total 476
telemt_me_writer_close_signal_drop_total 38
telemt_me_draining_writers_reap_progress_total 5124
telemt_me_writer_removed_unexpected_total 154
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 455
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4821
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 469
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4648
telemt_me_writer_teardown_success_total{mode="normal"} 5276
telemt_me_writer_teardown_noop_total 5124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10400
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.893179
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10400
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 38
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 128
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 439462
telemt_user_connections_current{user="hello"} 809
telemt_user_octets_from_client{user="hello"} 7157432888 (6.67 GB)
telemt_user_octets_to_client{user="hello"} 141938968128 (132.19 GB)
telemt_user_unique_ips_current{user="hello"} 530
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 89671.5 (24h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7092240
telemt_connections_bad_total 546006
telemt_connections_current 2825
telemt_connections_me_current 2825
telemt_handshake_timeouts_total 222256
telemt_upstream_connect_attempt_total 32195
telemt_upstream_connect_success_total 32132
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 32139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17516
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1396
telemt_me_reconnect_success_total 685
telemt_me_reader_eof_total 696
telemt_me_idle_close_by_peer_total 696
telemt_me_route_drop_no_conn_total 4416775
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5797762
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
telemt_desync_total 24171
telemt_desync_full_logged_total 8017
telemt_desync_suppressed_total 16154
telemt_desync_frames_bucket_total{bucket="1_2"} 5112
telemt_desync_frames_bucket_total{bucket="3_10"} 9539
telemt_desync_frames_bucket_total{bucket="gt_10"} 9520
telemt_pool_swap_total 96
telemt_pool_force_close_total 3254
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 530
telemt_me_draining_writers_reap_progress_total 29324
telemt_me_writer_removed_unexpected_total 669
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2504
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27081
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 235
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26070
telemt_me_writer_teardown_success_total{mode="normal"} 29585
telemt_me_writer_teardown_noop_total 29361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58946
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 144.105664
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58946
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 530
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 613
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 5790803
telemt_user_connections_current{user="hello"} 2825
telemt_user_octets_from_client{user="hello"} 99659752108 (92.82 GB)
telemt_user_octets_to_client{user="hello"} 1850694125836 (1.68 TB)
telemt_user_unique_ips_current{user="hello"} 1222
telemt_user_unique_ips_recent_window{user="hello"} 335
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 89672.0 (24h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5781341
telemt_connections_bad_total 568253
telemt_connections_current 2394
telemt_connections_me_current 2394
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 188624
telemt_upstream_connect_attempt_total 36209
telemt_upstream_connect_success_total 35887
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 36055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1694
telemt_me_reconnect_success_total 717
telemt_me_reader_eof_total 693
telemt_me_idle_close_by_peer_total 693
telemt_me_route_drop_no_conn_total 2000130
telemt_me_route_drop_channel_closed_total 226
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4312063
telemt_me_endpoint_quarantine_total 544
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 683
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
telemt_me_writers_active_current 46
telemt_desync_total 20724
telemt_desync_full_logged_total 6909
telemt_desync_suppressed_total 13815
telemt_desync_frames_bucket_total{bucket="1_2"} 5045
telemt_desync_frames_bucket_total{bucket="3_10"} 8009
telemt_desync_frames_bucket_total{bucket="gt_10"} 7670
telemt_pool_swap_total 98
telemt_pool_force_close_total 2980
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 334
telemt_me_draining_writers_reap_progress_total 27977
telemt_me_writer_removed_unexpected_total 670
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2421
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26157
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2781
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24997
telemt_me_writer_teardown_success_total{mode="normal"} 28578
telemt_me_writer_teardown_noop_total 27982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56560
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.716405
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56560
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 334
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 617
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 4298500
telemt_user_connections_current{user="hello"} 2394
telemt_user_octets_from_client{user="hello"} 130949946109 (121.96 GB)
telemt_user_octets_to_client{user="hello"} 1990970348231 (1.81 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1017
telemt_user_unique_ips_recent_window{user="hello"} 274
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 89636.3 (24h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5702247
telemt_connections_bad_total 517625
telemt_connections_current 2387
telemt_connections_me_current 2387
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 175401
telemt_upstream_connect_attempt_total 42641
telemt_upstream_connect_success_total 42362
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 42497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18652
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1042
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1743
telemt_me_reconnect_success_total 777
telemt_me_reader_eof_total 722
telemt_me_idle_close_by_peer_total 722
telemt_me_route_drop_no_conn_total 2039906
telemt_me_route_drop_channel_closed_total 107
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4291454
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
telemt_desync_total 20517
telemt_desync_full_logged_total 6734
telemt_desync_suppressed_total 13783
telemt_desync_frames_bucket_total{bucket="1_2"} 5112
telemt_desync_frames_bucket_total{bucket="3_10"} 7775
telemt_desync_frames_bucket_total{bucket="gt_10"} 7630
telemt_pool_swap_total 96
telemt_pool_force_close_total 2852
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 346
telemt_me_draining_writers_reap_progress_total 29438
telemt_me_writer_removed_unexpected_total 691
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2513
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27620
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2639
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26586
telemt_me_writer_teardown_success_total{mode="normal"} 30133
telemt_me_writer_teardown_noop_total 29448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59581
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.671782
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59581
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 346
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 671
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 4293320
telemt_user_connections_current{user="hello"} 2387
telemt_user_octets_from_client{user="hello"} 126517150403 (117.83 GB)
telemt_user_octets_to_client{user="hello"} 1960490699727 (1.78 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1033
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 89675.2 (24h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19433256
telemt_connections_bad_total 1308226
telemt_connections_current 3106
telemt_connections_me_current 3106
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 545459
telemt_upstream_connect_attempt_total 182241
telemt_upstream_connect_success_total 164963
telemt_upstream_connect_fail_total 15812
telemt_upstream_connect_attempts_per_request{bucket="1"} 180775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8853
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15812
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59674
telemt_me_reconnect_success_total 1929
telemt_me_reader_eof_total 1272
telemt_me_idle_close_by_peer_total 1271
telemt_me_route_drop_no_conn_total 39349712
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15942447
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
telemt_me_writers_active_current 48
telemt_desync_total 30172
telemt_desync_full_logged_total 8912
telemt_desync_suppressed_total 21260
telemt_desync_frames_bucket_total{bucket="1_2"} 6611
telemt_desync_frames_bucket_total{bucket="3_10"} 13393
telemt_desync_frames_bucket_total{bucket="gt_10"} 10168
telemt_pool_swap_total 91
telemt_pool_force_close_total 3070
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 700
telemt_me_draining_writers_reap_progress_total 27644
telemt_me_writer_removed_unexpected_total 1810
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3770
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25428
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2570
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 500
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24574
telemt_me_writer_teardown_success_total{mode="normal"} 29198
telemt_me_writer_teardown_noop_total 27670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56868
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 205.186682
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56868
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 700
telemt_me_refill_failed_total 3519
telemt_me_writer_restored_same_endpoint_total 1350
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14245
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 16067469
telemt_user_connections_current{user="hello"} 3106
telemt_user_octets_from_client{user="hello"} 163312729402 (152.10 GB)
telemt_user_octets_to_client{user="hello"} 1004486451502 (935.50 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1318
telemt_user_unique_ips_recent_window{user="hello"} 390
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 89642.6 (24h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5561988
telemt_connections_bad_total 527965
telemt_connections_current 2634
telemt_connections_me_current 2634
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 114835
telemt_upstream_connect_attempt_total 45763
telemt_upstream_connect_success_total 45261
telemt_upstream_connect_fail_total 417
telemt_upstream_connect_attempts_per_request{bucket="1"} 45678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18913
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 329
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 417
telemt_me_reconnect_attempts_total 11125
telemt_me_reconnect_success_total 1287
telemt_me_reader_eof_total 1217
telemt_me_idle_close_by_peer_total 1217
telemt_me_route_drop_no_conn_total 2302940
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4328972
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
telemt_me_writers_active_current 43
telemt_desync_total 21651
telemt_desync_full_logged_total 7512
telemt_desync_suppressed_total 14139
telemt_desync_frames_bucket_total{bucket="1_2"} 4131
telemt_desync_frames_bucket_total{bucket="3_10"} 8415
telemt_desync_frames_bucket_total{bucket="gt_10"} 9105
telemt_pool_swap_total 91
telemt_pool_force_close_total 2703
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 340
telemt_me_draining_writers_reap_progress_total 30258
telemt_me_writer_removed_unexpected_total 1196
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3070
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28398
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2335
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27555
telemt_me_writer_teardown_success_total{mode="normal"} 31468
telemt_me_writer_teardown_noop_total 30259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61727
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.577079
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61727
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 340
telemt_me_refill_failed_total 593
telemt_me_writer_restored_same_endpoint_total 1088
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 1512
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4318456
telemt_user_connections_current{user="hello"} 2634
telemt_user_octets_from_client{user="hello"} 115332227745 (107.41 GB)
telemt_user_octets_to_client{user="hello"} 1755155443051 (1.60 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1151
telemt_user_unique_ips_recent_window{user="hello"} 324
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 26478.4 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3328244
telemt_connections_bad_total 121488
telemt_connections_current 2004
telemt_connections_me_current 2004
telemt_handshake_timeouts_total 1405442
telemt_upstream_connect_attempt_total 8741
telemt_upstream_connect_success_total 8628
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 8735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 2260
telemt_me_reconnect_success_total 284
telemt_me_reader_eof_total 226
telemt_me_idle_close_by_peer_total 226
telemt_me_route_drop_no_conn_total 946967
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1592317
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
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 8871
telemt_desync_full_logged_total 2956
telemt_desync_suppressed_total 5915
telemt_desync_frames_bucket_total{bucket="1_2"} 1594
telemt_desync_frames_bucket_total{bucket="3_10"} 3398
telemt_desync_frames_bucket_total{bucket="gt_10"} 3879
telemt_pool_swap_total 28
telemt_pool_force_close_total 905
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 7606
telemt_me_writer_removed_unexpected_total 243
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 703
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7154
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 793
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6701
telemt_me_writer_teardown_success_total{mode="normal"} 7857
telemt_me_writer_teardown_noop_total 7607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15464
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.358324
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15464
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 231
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1587767
telemt_user_connections_current{user="hello"} 2004
telemt_user_octets_from_client{user="hello"} 46357912392 (43.17 GB)
telemt_user_octets_to_client{user="hello"} 674365758356 (628.05 GB)
telemt_user_unique_ips_current{user="hello"} 888
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 7449.6 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102365
telemt_connections_bad_total 1194
telemt_connections_current 459
telemt_connections_me_current 459
telemt_handshake_timeouts_total 3058
telemt_upstream_connect_attempt_total 3187
telemt_upstream_connect_success_total 3178
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 3186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 70
telemt_me_reconnect_success_total 39
telemt_me_reader_eof_total 39
telemt_me_idle_close_by_peer_total 39
telemt_me_route_drop_no_conn_total 28546
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87297
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
telemt_desync_total 829
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 636
telemt_desync_frames_bucket_total{bucket="1_2"} 361
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 8
telemt_pool_force_close_total 217
telemt_me_writer_close_signal_drop_total 11
telemt_me_draining_writers_reap_progress_total 2775
telemt_me_writer_removed_unexpected_total 39
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2622
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2558
telemt_me_writer_teardown_success_total{mode="normal"} 2814
telemt_me_writer_teardown_noop_total 2775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5589
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.496711
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5589
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 11
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 87159
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 2057211268 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 58970681272 (54.92 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 89647.2 (24h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6616665
telemt_connections_bad_total 670095
telemt_connections_current 2970
telemt_connections_me_current 2970
telemt_handshake_timeouts_total 191249
telemt_upstream_connect_attempt_total 33908
telemt_upstream_connect_success_total 33772
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 33871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16993
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_reconnect_attempts_total 1415
telemt_me_reconnect_success_total 719
telemt_me_reader_eof_total 695
telemt_me_idle_close_by_peer_total 695
telemt_me_route_drop_no_conn_total 2033307
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5069353
telemt_me_endpoint_quarantine_total 593
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 682
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
telemt_desync_total 19438
telemt_desync_full_logged_total 6481
telemt_desync_suppressed_total 12957
telemt_desync_frames_bucket_total{bucket="1_2"} 4734
telemt_desync_frames_bucket_total{bucket="3_10"} 7107
telemt_desync_frames_bucket_total{bucket="gt_10"} 7597
telemt_pool_swap_total 99
telemt_pool_force_close_total 2711
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 341
telemt_me_draining_writers_reap_progress_total 30443
telemt_me_writer_removed_unexpected_total 676
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2478
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28650
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2626
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27732
telemt_me_writer_teardown_success_total{mode="normal"} 31128
telemt_me_writer_teardown_noop_total 30445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61573
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.120338
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61573
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 341
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 643
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 5045031
telemt_user_connections_current{user="hello"} 2970
telemt_user_octets_from_client{user="hello"} 101532897468 (94.56 GB)
telemt_user_octets_to_client{user="hello"} 2365056263400 (2.15 TB)
telemt_user_unique_ips_current{user="hello"} 1101
telemt_user_unique_ips_recent_window{user="hello"} 296
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 89643.9 (24h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5634550
telemt_connections_bad_total 530676
telemt_connections_current 2801
telemt_connections_me_current 2801
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 160500
telemt_upstream_connect_attempt_total 50193
telemt_upstream_connect_success_total 49819
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 50134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18845
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_reconnect_attempts_total 4585
telemt_me_reconnect_success_total 1006
telemt_me_reader_eof_total 895
telemt_me_idle_close_by_peer_total 895
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2089162
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4436343
telemt_me_endpoint_quarantine_total 704
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 681
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
telemt_desync_total 18027
telemt_desync_full_logged_total 6089
telemt_desync_suppressed_total 11938
telemt_desync_frames_bucket_total{bucket="1_2"} 4449
telemt_desync_frames_bucket_total{bucket="3_10"} 6605
telemt_desync_frames_bucket_total{bucket="gt_10"} 6973
telemt_pool_swap_total 97
telemt_pool_force_close_total 2648
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 340
telemt_me_draining_writers_reap_progress_total 29560
telemt_me_writer_removed_unexpected_total 906
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2953
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27555
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2444
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 204
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26912
telemt_me_writer_teardown_success_total{mode="normal"} 30508
telemt_me_writer_teardown_noop_total 29564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60072
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.056501
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60072
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 340
telemt_me_refill_failed_total 204
telemt_me_writer_restored_same_endpoint_total 775
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 4440197
telemt_user_connections_current{user="hello"} 2801
telemt_user_octets_from_client{user="hello"} 84588566661 (78.78 GB)
telemt_user_octets_to_client{user="hello"} 1884140708820 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1149
telemt_user_unique_ips_recent_window{user="hello"} 322
```