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

# Server Metrics 2026-03-22 21:16:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 87023.4 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3193643
telemt_connections_bad_total 231399
telemt_connections_current 889
telemt_connections_me_current 889
telemt_handshake_timeouts_total 102142
telemt_upstream_connect_attempt_total 31901
telemt_upstream_connect_success_total 31900
telemt_upstream_connect_attempts_per_request{bucket="1"} 31900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20802
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1287
telemt_me_reconnect_success_total 534
telemt_me_reader_eof_total 545
telemt_me_idle_close_by_peer_total 545
telemt_me_route_drop_no_conn_total 2832807
telemt_me_route_drop_channel_closed_total 1139
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2690173
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 588
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 674
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
telemt_desync_total 11615
telemt_desync_full_logged_total 3645
telemt_desync_suppressed_total 7970
telemt_desync_frames_bucket_total{bucket="1_2"} 3145
telemt_desync_frames_bucket_total{bucket="3_10"} 4251
telemt_desync_frames_bucket_total{bucket="gt_10"} 4219
telemt_pool_swap_total 96
telemt_pool_force_close_total 2993
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 604
telemt_me_draining_writers_reap_progress_total 29163
telemt_me_writer_removed_unexpected_total 529
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27273
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2938
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26170
telemt_me_writer_teardown_success_total{mode="normal"} 29397
telemt_me_writer_teardown_noop_total 29174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58571
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 332.500959
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58571
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 604
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 475
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 2680437
telemt_user_connections_current{user="hello"} 889
telemt_user_octets_from_client{user="hello"} 39117414532 (36.43 GB)
telemt_user_octets_to_client{user="hello"} 722194553292 (672.60 GB)
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 100389.2 (27h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3895657
telemt_connections_bad_total 345128
telemt_connections_current 426
telemt_connections_me_current 426
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99072
telemt_upstream_connect_attempt_total 60210
telemt_upstream_connect_success_total 59476
telemt_upstream_connect_fail_total 648
telemt_upstream_connect_attempts_per_request{bucket="1"} 60124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 648
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6906
telemt_me_reconnect_success_total 2694
telemt_me_reader_eof_total 2641
telemt_me_idle_close_by_peer_total 2641
telemt_me_route_drop_no_conn_total 3623611
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3105495
telemt_me_endpoint_quarantine_total 760
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 774
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 12569
telemt_desync_full_logged_total 7042
telemt_desync_suppressed_total 5527
telemt_desync_frames_bucket_total{bucket="1_2"} 2842
telemt_desync_frames_bucket_total{bucket="3_10"} 4934
telemt_desync_frames_bucket_total{bucket="gt_10"} 4793
telemt_pool_swap_total 94
telemt_pool_force_close_total 2858
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 236
telemt_me_draining_writers_reap_progress_total 39991
telemt_me_writer_removed_unexpected_total 2584
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4868
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37727
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2431
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37133
telemt_me_writer_teardown_success_total{mode="normal"} 42595
telemt_me_writer_teardown_noop_total 39992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82587
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.371102
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82587
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 236
telemt_me_refill_failed_total 168
telemt_me_writer_restored_same_endpoint_total 2373
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 3116173
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 40892895107 (38.08 GB)
telemt_user_octets_to_client{user="hello"} 759293895098 (707.15 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 175249.2 (48h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16074502
telemt_connections_bad_total 1557457
telemt_connections_current 1447
telemt_connections_me_current 1447
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 394677
telemt_upstream_connect_attempt_total 77706
telemt_upstream_connect_success_total 77606
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 77623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37354
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2841
telemt_me_reconnect_success_total 1476
telemt_me_reader_eof_total 1421
telemt_me_idle_close_by_peer_total 1419
telemt_me_route_drop_no_conn_total 14010145
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12814236
telemt_me_endpoint_quarantine_total 1114
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1306
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
telemt_desync_total 52902
telemt_desync_full_logged_total 16700
telemt_desync_suppressed_total 36202
telemt_desync_frames_bucket_total{bucket="1_2"} 11767
telemt_desync_frames_bucket_total{bucket="3_10"} 20613
telemt_desync_frames_bucket_total{bucket="gt_10"} 20522
telemt_pool_swap_total 189
telemt_pool_force_close_total 6356
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1024
telemt_me_draining_writers_reap_progress_total 57708
telemt_me_writer_removed_unexpected_total 1371
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5048
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53310
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5886
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51352
telemt_me_writer_teardown_success_total{mode="normal"} 58358
telemt_me_writer_teardown_noop_total 57759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116117
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 314.757267
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116117
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1024
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1275
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12814562
telemt_user_connections_current{user="hello"} 1447
telemt_user_octets_from_client{user="hello"} 188370811105 (175.43 GB)
telemt_user_octets_to_client{user="hello"} 3433611524591 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 612
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 175250.8 (48h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11655361
telemt_connections_bad_total 1176712
telemt_connections_current 1053
telemt_connections_me_current 1053
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343426
telemt_upstream_connect_attempt_total 92267
telemt_upstream_connect_success_total 90964
telemt_upstream_connect_fail_total 857
telemt_upstream_connect_attempts_per_request{bucket="1"} 91821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37404
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3790
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 857
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4277
telemt_me_reconnect_success_total 1785
telemt_me_reader_eof_total 1643
telemt_me_idle_close_by_peer_total 1643
telemt_me_route_drop_no_conn_total 4528145
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8681517
telemt_me_endpoint_quarantine_total 1114
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1328
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 38406
telemt_desync_full_logged_total 12919
telemt_desync_suppressed_total 25487
telemt_desync_frames_bucket_total{bucket="1_2"} 9485
telemt_desync_frames_bucket_total{bucket="3_10"} 14777
telemt_desync_frames_bucket_total{bucket="gt_10"} 14144
telemt_pool_swap_total 186
telemt_pool_force_close_total 5729
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 705
telemt_me_draining_writers_reap_progress_total 56141
telemt_me_writer_removed_unexpected_total 1681
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5200
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52470
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5217
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50412
telemt_me_writer_teardown_success_total{mode="normal"} 57670
telemt_me_writer_teardown_noop_total 56166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113836
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.154320
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113836
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 705
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1518
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8619447
telemt_user_connections_current{user="hello"} 1053
telemt_user_octets_from_client{user="hello"} 216598370668 (201.72 GB)
telemt_user_octets_to_client{user="hello"} 3901945451775 (3.55 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 175216.0 (48h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10906247
telemt_connections_bad_total 946180
telemt_connections_current 761
telemt_connections_me_current 761
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344589
telemt_upstream_connect_attempt_total 75880
telemt_upstream_connect_success_total 74510
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 74707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1777
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2281
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1419
telemt_me_reconnect_attempts_total 5363
telemt_me_reconnect_success_total 2182
telemt_me_reader_eof_total 1916
telemt_me_idle_close_by_peer_total 1915
telemt_me_route_drop_no_conn_total 5307985
telemt_me_route_drop_channel_closed_total 382
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8253399
telemt_me_endpoint_quarantine_total 1204
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1282
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 66
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
telemt_desync_total 37826
telemt_desync_full_logged_total 12531
telemt_desync_suppressed_total 25295
telemt_desync_frames_bucket_total{bucket="1_2"} 9556
telemt_desync_frames_bucket_total{bucket="3_10"} 14468
telemt_desync_frames_bucket_total{bucket="gt_10"} 13802
telemt_pool_swap_total 183
telemt_pool_force_close_total 5667
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 722
telemt_me_draining_writers_reap_progress_total 56277
telemt_me_writer_removed_unexpected_total 2067
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5785
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52483
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5102
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50610
telemt_me_writer_teardown_success_total{mode="normal"} 58268
telemt_me_writer_teardown_noop_total 56348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114616
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.206429
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114616
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 722
telemt_me_refill_failed_total 168
telemt_me_writer_restored_same_endpoint_total 1883
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 8245430
telemt_user_connections_current{user="hello"} 761
telemt_user_octets_from_client{user="hello"} 191731437777 (178.56 GB)
telemt_user_octets_to_client{user="hello"} 3429903769665 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 45495.0 (12h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10973625
telemt_connections_bad_total 666358
telemt_connections_current 1486
telemt_connections_me_current 1486
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 243405
telemt_upstream_connect_attempt_total 49953
telemt_upstream_connect_success_total 47431
telemt_upstream_connect_fail_total 1730
telemt_upstream_connect_attempts_per_request{bucket="1"} 49161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15528
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5982
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1730
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6970
telemt_me_reconnect_success_total 1019
telemt_me_reader_eof_total 627
telemt_me_idle_close_by_peer_total 626
telemt_me_route_drop_no_conn_total 25239706
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9112283
telemt_me_endpoint_quarantine_total 314
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 361
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
telemt_me_writers_active_current 47
telemt_desync_total 15290
telemt_desync_full_logged_total 4064
telemt_desync_suppressed_total 11226
telemt_desync_frames_bucket_total{bucket="1_2"} 2881
telemt_desync_frames_bucket_total{bucket="3_10"} 6207
telemt_desync_frames_bucket_total{bucket="gt_10"} 6202
telemt_pool_swap_total 46
telemt_pool_force_close_total 1638
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 446
telemt_me_draining_writers_reap_progress_total 13193
telemt_me_writer_removed_unexpected_total 907
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1972
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12083
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1332
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11555
telemt_me_writer_teardown_success_total{mode="normal"} 14055
telemt_me_writer_teardown_noop_total 13212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27267
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.098661
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27267
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 446
telemt_me_refill_failed_total 324
telemt_me_writer_restored_same_endpoint_total 663
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 9137036
telemt_user_connections_current{user="hello"} 1486
telemt_user_octets_from_client{user="hello"} 84877009940 (79.05 GB)
telemt_user_octets_to_client{user="hello"} 536869468954 (500.00 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 576
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 175220.9 (48h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10808333
telemt_connections_bad_total 910332
telemt_connections_current 1246
telemt_connections_me_current 1246
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 237574
telemt_upstream_connect_attempt_total 104785
telemt_upstream_connect_success_total 103687
telemt_upstream_connect_fail_total 936
telemt_upstream_connect_attempts_per_request{bucket="1"} 104623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 936
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72454
telemt_me_reconnect_success_total 2857
telemt_me_reader_eof_total 2552
telemt_me_idle_close_by_peer_total 2550
telemt_me_route_drop_no_conn_total 5226599
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8542914
telemt_me_endpoint_quarantine_total 1155
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1311
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
telemt_me_writers_active_current 43
telemt_desync_total 45540
telemt_desync_full_logged_total 15545
telemt_desync_suppressed_total 29995
telemt_desync_frames_bucket_total{bucket="1_2"} 9236
telemt_desync_frames_bucket_total{bucket="3_10"} 17444
telemt_desync_frames_bucket_total{bucket="gt_10"} 18860
telemt_pool_swap_total 179
telemt_pool_force_close_total 5346
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 645
telemt_me_draining_writers_reap_progress_total 60148
telemt_me_writer_removed_unexpected_total 2587
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6346
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56418
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4616
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54802
telemt_me_writer_teardown_success_total{mode="normal"} 62764
telemt_me_writer_teardown_noop_total 60149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122913
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.116017
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122913
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 645
telemt_me_refill_failed_total 4287
telemt_me_writer_restored_same_endpoint_total 2406
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8546049
telemt_user_connections_current{user="hello"} 1246
telemt_user_octets_from_client{user="hello"} 193184620153 (179.92 GB)
telemt_user_octets_to_client{user="hello"} 3257976668372 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 518
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 112057.1 (31h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11422510
telemt_connections_bad_total 456704
telemt_connections_current 929
telemt_connections_me_current 929
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4681469
telemt_upstream_connect_attempt_total 52954
telemt_upstream_connect_success_total 52559
telemt_upstream_connect_fail_total 385
telemt_upstream_connect_attempts_per_request{bucket="1"} 52944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 385
telemt_me_reconnect_attempts_total 48656
telemt_me_reconnect_success_total 1697
telemt_me_reader_eof_total 1358
telemt_me_idle_close_by_peer_total 1357
telemt_me_route_drop_no_conn_total 4059553
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5510479
telemt_me_endpoint_quarantine_total 725
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 848
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30953
telemt_desync_full_logged_total 10521
telemt_desync_suppressed_total 20432
telemt_desync_frames_bucket_total{bucket="1_2"} 6149
telemt_desync_frames_bucket_total{bucket="3_10"} 12248
telemt_desync_frames_bucket_total{bucket="gt_10"} 12556
telemt_pool_swap_total 118
telemt_pool_force_close_total 3591
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 360
telemt_me_draining_writers_reap_progress_total 39184
telemt_me_writer_removed_unexpected_total 1416
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3417
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37219
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3150
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35593
telemt_me_writer_teardown_success_total{mode="normal"} 40636
telemt_me_writer_teardown_noop_total 39191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79827
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.614615
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79827
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 360
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1507
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5503176
telemt_user_connections_current{user="hello"} 929
telemt_user_octets_from_client{user="hello"} 117963475804 (109.86 GB)
telemt_user_octets_to_client{user="hello"} 2110941111186 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 397
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 93028.2 (25h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1409408
telemt_connections_bad_total 34415
telemt_connections_current 825
telemt_connections_me_current 825
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 26084
telemt_upstream_connect_attempt_total 43683
telemt_upstream_connect_success_total 43546
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 43656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 749
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2044
telemt_me_reconnect_success_total 831
telemt_me_reader_eof_total 813
telemt_me_idle_close_by_peer_total 813
telemt_me_route_drop_no_conn_total 490392
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1251130
telemt_me_endpoint_quarantine_total 759
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 767
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 7713
telemt_desync_full_logged_total 2363
telemt_desync_suppressed_total 5350
telemt_desync_frames_bucket_total{bucket="1_2"} 1805
telemt_desync_frames_bucket_total{bucket="3_10"} 2980
telemt_desync_frames_bucket_total{bucket="gt_10"} 2928
telemt_pool_swap_total 100
telemt_pool_force_close_total 2603
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 36484
telemt_me_writer_removed_unexpected_total 783
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2883
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34417
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2516
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33881
telemt_me_writer_teardown_success_total{mode="normal"} 37300
telemt_me_writer_teardown_noop_total 36488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73788
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.827384
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73788
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 705
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1247113
telemt_user_connections_current{user="hello"} 825
telemt_user_octets_from_client{user="hello"} 24294937689 (22.63 GB)
telemt_user_octets_to_client{user="hello"} 527341158331 (491.12 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 175225.6 (48h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13144061
telemt_connections_bad_total 1554810
telemt_connections_current 1289
telemt_connections_me_current 1289
telemt_handshake_timeouts_total 377118
telemt_upstream_connect_attempt_total 66567
telemt_upstream_connect_success_total 66234
telemt_upstream_connect_fail_total 198
telemt_upstream_connect_attempts_per_request{bucket="1"} 66432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 198
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2586
telemt_me_reconnect_success_total 1362
telemt_me_reader_eof_total 1330
telemt_me_idle_close_by_peer_total 1330
telemt_me_route_drop_no_conn_total 4457448
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9935292
telemt_me_endpoint_quarantine_total 1190
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1313
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
telemt_desync_total 41414
telemt_desync_full_logged_total 13500
telemt_desync_suppressed_total 27914
telemt_desync_frames_bucket_total{bucket="1_2"} 9962
telemt_desync_frames_bucket_total{bucket="3_10"} 15245
telemt_desync_frames_bucket_total{bucket="gt_10"} 16207
telemt_pool_swap_total 194
telemt_pool_force_close_total 5313
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 656
telemt_me_draining_writers_reap_progress_total 60012
telemt_me_writer_removed_unexpected_total 1279
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4874
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56458
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54699
telemt_me_writer_teardown_success_total{mode="normal"} 61332
telemt_me_writer_teardown_noop_total 60014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121346
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.536232
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121346
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 656
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1193
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 9902176
telemt_user_connections_current{user="hello"} 1289
telemt_user_octets_from_client{user="hello"} 193490364612 (180.20 GB)
telemt_user_octets_to_client{user="hello"} 4380598741008 (3.98 TB)
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 175222.0 (48h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11421345
telemt_connections_bad_total 1291812
telemt_connections_current 962
telemt_connections_me_current 962
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 301012
telemt_upstream_connect_attempt_total 93001
telemt_upstream_connect_success_total 92165
telemt_upstream_connect_fail_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 92794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 629
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9974
telemt_me_reconnect_success_total 2400
telemt_me_reader_eof_total 2244
telemt_me_idle_close_by_peer_total 2243
telemt_me_seq_mismatch_total 80
telemt_me_route_drop_no_conn_total 5617273
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8836309
telemt_me_endpoint_quarantine_total 1340
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1313
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
telemt_me_writers_active_current 44
telemt_desync_total 40794
telemt_desync_full_logged_total 13102
telemt_desync_suppressed_total 27692
telemt_desync_frames_bucket_total{bucket="1_2"} 10367
telemt_desync_frames_bucket_total{bucket="3_10"} 15065
telemt_desync_frames_bucket_total{bucket="gt_10"} 15362
telemt_pool_swap_total 184
telemt_pool_force_close_total 5111
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 643
telemt_me_draining_writers_reap_progress_total 59762
telemt_me_writer_removed_unexpected_total 2275
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6211
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55904
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4640
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54651
telemt_me_writer_teardown_success_total{mode="normal"} 62115
telemt_me_writer_teardown_noop_total 59767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121882
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.251777
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121882
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 643
telemt_me_refill_failed_total 391
telemt_me_writer_restored_same_endpoint_total 1953
telemt_me_writer_restored_fallback_total 111
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 8841781
telemt_user_connections_current{user="hello"} 962
telemt_user_octets_from_client{user="hello"} 156328185877 (145.59 GB)
telemt_user_octets_to_client{user="hello"} 3434808388799 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 403
telemt_user_unique_ips_recent_window{user="hello"} 117
```