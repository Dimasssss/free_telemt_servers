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

# Server Metrics 2026-03-22 04:02:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 24980.1 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389382
telemt_connections_bad_total 24874
telemt_connections_current 1025
telemt_connections_me_current 1025
telemt_handshake_timeouts_total 21256
telemt_upstream_connect_attempt_total 10478
telemt_upstream_connect_success_total 10477
telemt_upstream_connect_attempts_per_request{bucket="1"} 10477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 289
telemt_me_reconnect_success_total 163
telemt_me_reader_eof_total 159
telemt_me_idle_close_by_peer_total 159
telemt_me_route_drop_no_conn_total 77582
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322602
telemt_me_endpoint_quarantine_total 198
telemt_me_single_endpoint_shadow_rotate_total 208
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 2926
telemt_desync_full_logged_total 798
telemt_desync_suppressed_total 2128
telemt_desync_frames_bucket_total{bucket="1_2"} 1008
telemt_desync_frames_bucket_total{bucket="3_10"} 1105
telemt_desync_frames_bucket_total{bucket="gt_10"} 813
telemt_pool_swap_total 27
telemt_pool_force_close_total 710
telemt_me_writer_close_signal_drop_total 50
telemt_me_draining_writers_reap_progress_total 9468
telemt_me_writer_removed_unexpected_total 157
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 627
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8990
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 705
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8758
telemt_me_writer_teardown_success_total{mode="normal"} 9617
telemt_me_writer_teardown_noop_total 9469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19086
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.746962
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19086
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 50
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 146
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 321690
telemt_user_connections_current{user="hello"} 1025
telemt_user_octets_from_client{user="hello"} 4122637808 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 110369090044 (102.79 GB)
telemt_user_unique_ips_current{user="hello"} 450
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 38346.3 (10h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 854582
telemt_connections_bad_total 56914
telemt_connections_current 658
telemt_connections_me_current 658
telemt_handshake_timeouts_total 30827
telemt_upstream_connect_attempt_total 17975
telemt_upstream_connect_success_total 17697
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 17951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_reconnect_attempts_total 1498
telemt_me_reconnect_success_total 549
telemt_me_reader_eof_total 486
telemt_me_idle_close_by_peer_total 486
telemt_me_route_drop_no_conn_total 352291
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 676268
telemt_me_endpoint_quarantine_total 362
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 312
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
telemt_desync_total 2877
telemt_desync_full_logged_total 1660
telemt_desync_suppressed_total 1217
telemt_desync_frames_bucket_total{bucket="1_2"} 609
telemt_desync_frames_bucket_total{bucket="3_10"} 1091
telemt_desync_frames_bucket_total{bucket="gt_10"} 1177
telemt_pool_swap_total 41
telemt_pool_force_close_total 1098
telemt_me_writer_close_signal_drop_total 78
telemt_me_draining_writers_reap_progress_total 15962
telemt_me_writer_removed_unexpected_total 462
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1322
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15113
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1076
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14864
telemt_me_writer_teardown_success_total{mode="normal"} 16435
telemt_me_writer_teardown_noop_total 15962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32397
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.868169
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32397
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 78
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 407
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 675236
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 10955165960 (10.20 GB)
telemt_user_octets_to_client{user="hello"} 241880256304 (225.27 GB)
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 113206.6 (31h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7924205
telemt_connections_bad_total 658353
telemt_connections_current 2268
telemt_connections_me_current 2268
telemt_handshake_timeouts_total 260770
telemt_upstream_connect_attempt_total 42252
telemt_upstream_connect_success_total 42175
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 42182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1627
telemt_me_reconnect_success_total 845
telemt_me_reader_eof_total 854
telemt_me_idle_close_by_peer_total 854
telemt_me_route_drop_no_conn_total 4566976
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6401133
telemt_me_endpoint_quarantine_total 730
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 849
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
telemt_me_writers_active_current 44
telemt_desync_total 26854
telemt_desync_full_logged_total 8916
telemt_desync_suppressed_total 17938
telemt_desync_frames_bucket_total{bucket="1_2"} 5800
telemt_desync_frames_bucket_total{bucket="3_10"} 10490
telemt_desync_frames_bucket_total{bucket="gt_10"} 10564
telemt_pool_swap_total 122
telemt_pool_force_close_total 4018
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 38554
telemt_me_writer_removed_unexpected_total 822
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3207
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35704
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3778
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34536
telemt_me_writer_teardown_success_total{mode="normal"} 38911
telemt_me_writer_teardown_noop_total 38598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77509
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 162.426231
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77509
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 753
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6393006
telemt_user_connections_current{user="hello"} 2268
telemt_user_octets_from_client{user="hello"} 108836895592 (101.36 GB)
telemt_user_octets_to_client{user="hello"} 2145265161332 (1.95 TB)
telemt_user_unique_ips_current{user="hello"} 1086
telemt_user_unique_ips_recent_window{user="hello"} 304
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 113207.7 (31h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6555597
telemt_connections_bad_total 593238
telemt_connections_current 2324
telemt_connections_me_current 2324
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 217800
telemt_upstream_connect_attempt_total 46201
telemt_upstream_connect_success_total 45807
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 46004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22547
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1971
telemt_me_reconnect_success_total 901
telemt_me_reader_eof_total 875
telemt_me_idle_close_by_peer_total 875
telemt_me_route_drop_no_conn_total 2283211
telemt_me_route_drop_channel_closed_total 277
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4890411
telemt_me_endpoint_quarantine_total 713
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 873
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22964
telemt_desync_full_logged_total 7834
telemt_desync_suppressed_total 15130
telemt_desync_frames_bucket_total{bucket="1_2"} 5520
telemt_desync_frames_bucket_total{bucket="3_10"} 8922
telemt_desync_frames_bucket_total{bucket="gt_10"} 8522
telemt_pool_swap_total 123
telemt_pool_force_close_total 3650
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 37008
telemt_me_writer_removed_unexpected_total 857
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3069
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34736
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3433
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 217
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33358
telemt_me_writer_teardown_success_total{mode="normal"} 37805
telemt_me_writer_teardown_noop_total 37014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74819
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.494118
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74819
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 788
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4812147
telemt_user_connections_current{user="hello"} 2324
telemt_user_octets_from_client{user="hello"} 142630595973 (132.84 GB)
telemt_user_octets_to_client{user="hello"} 2285502984067 (2.08 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1123
telemt_user_unique_ips_recent_window{user="hello"} 333
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 113171.5 (31h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6424040
telemt_connections_bad_total 551424
telemt_connections_current 1634
telemt_connections_me_current 1634
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 210620
telemt_upstream_connect_attempt_total 52538
telemt_upstream_connect_success_total 52072
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 52213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24059
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2256
telemt_me_reconnect_success_total 1010
telemt_me_reader_eof_total 948
telemt_me_idle_close_by_peer_total 948
telemt_me_route_drop_no_conn_total 2221028
telemt_me_route_drop_channel_closed_total 127
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4773290
telemt_me_endpoint_quarantine_total 795
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 846
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_active_current 90
telemt_desync_total 22854
telemt_desync_full_logged_total 7713
telemt_desync_suppressed_total 15141
telemt_desync_frames_bucket_total{bucket="1_2"} 5579
telemt_desync_frames_bucket_total{bucket="3_10"} 8760
telemt_desync_frames_bucket_total{bucket="gt_10"} 8515
telemt_pool_swap_total 121
telemt_pool_force_close_total 3507
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 400
telemt_me_draining_writers_reap_progress_total 38085
telemt_me_writer_removed_unexpected_total 935
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3226
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35811
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3292
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34578
telemt_me_writer_teardown_success_total{mode="normal"} 39037
telemt_me_writer_teardown_noop_total 38097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77134
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.183465
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77134
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 400
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 884
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4768462
telemt_user_connections_current{user="hello"} 1634
telemt_user_octets_from_client{user="hello"} 135226122531 (125.94 GB)
telemt_user_octets_to_client{user="hello"} 2184519147703 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 804
telemt_user_unique_ips_recent_window{user="hello"} 300
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 113210.4 (31h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20686667
telemt_connections_bad_total 1701958
telemt_connections_current 3080
telemt_connections_me_current 3080
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 624209
telemt_upstream_connect_attempt_total 203055
telemt_upstream_connect_success_total 184767
telemt_upstream_connect_fail_total 16469
telemt_upstream_connect_attempts_per_request{bucket="1"} 201236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44360
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8949
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16469
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65149
telemt_me_reconnect_success_total 2415
telemt_me_reader_eof_total 1499
telemt_me_idle_close_by_peer_total 1498
telemt_me_route_drop_no_conn_total 39561934
telemt_me_route_drop_channel_closed_total 127
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16665387
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 882
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 887
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 32274
telemt_desync_full_logged_total 9714
telemt_desync_suppressed_total 22560
telemt_desync_frames_bucket_total{bucket="1_2"} 7006
telemt_desync_frames_bucket_total{bucket="3_10"} 14313
telemt_desync_frames_bucket_total{bucket="gt_10"} 10955
telemt_pool_swap_total 117
telemt_pool_force_close_total 3773
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 829
telemt_me_draining_writers_reap_progress_total 35516
telemt_me_writer_removed_unexpected_total 2240
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4796
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32703
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3244
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 529
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31743
telemt_me_writer_teardown_success_total{mode="normal"} 37499
telemt_me_writer_teardown_noop_total 35543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73042
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 216.554929
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73042
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 829
telemt_me_refill_failed_total 3808
telemt_me_writer_restored_same_endpoint_total 1640
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 16800166
telemt_user_connections_current{user="hello"} 3080
telemt_user_octets_from_client{user="hello"} 234358096844 (218.26 GB)
telemt_user_octets_to_client{user="hello"} 1259705135619 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1342
telemt_user_unique_ips_recent_window{user="hello"} 396
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 113177.7 (31h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6192013
telemt_connections_bad_total 600333
telemt_connections_current 2102
telemt_connections_me_current 2102
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 130469
telemt_upstream_connect_attempt_total 61035
telemt_upstream_connect_success_total 60339
telemt_upstream_connect_fail_total 594
telemt_upstream_connect_attempts_per_request{bucket="1"} 60933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24988
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 594
telemt_me_reconnect_attempts_total 69764
telemt_me_reconnect_success_total 1826
telemt_me_reader_eof_total 1609
telemt_me_idle_close_by_peer_total 1608
telemt_me_route_drop_no_conn_total 2413897
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4804963
telemt_me_endpoint_quarantine_total 768
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 860
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 24026
telemt_desync_full_logged_total 8426
telemt_desync_suppressed_total 15600
telemt_desync_frames_bucket_total{bucket="1_2"} 4684
telemt_desync_frames_bucket_total{bucket="3_10"} 9286
telemt_desync_frames_bucket_total{bucket="gt_10"} 10056
telemt_pool_swap_total 117
telemt_pool_force_close_total 3344
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 402
telemt_me_draining_writers_reap_progress_total 40035
telemt_me_writer_removed_unexpected_total 1646
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4072
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37641
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2943
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36691
telemt_me_writer_teardown_success_total{mode="normal"} 41713
telemt_me_writer_teardown_noop_total 40036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81749
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.267049
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81749
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 402
telemt_me_refill_failed_total 4210
telemt_me_writer_restored_same_endpoint_total 1534
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 4797429
telemt_user_connections_current{user="hello"} 2102
telemt_user_octets_from_client{user="hello"} 126315462184 (117.64 GB)
telemt_user_octets_to_client{user="hello"} 1970922470750 (1.79 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1003
telemt_user_unique_ips_recent_window{user="hello"} 276
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 50013.5 (13h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4132553
telemt_connections_bad_total 175964
telemt_connections_current 1864
telemt_connections_me_current 1864
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1662223
telemt_upstream_connect_attempt_total 29839
telemt_upstream_connect_success_total 29643
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 29832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_reconnect_attempts_total 45964
telemt_me_reconnect_success_total 1001
telemt_me_reader_eof_total 687
telemt_me_idle_close_by_peer_total 687
telemt_me_route_drop_no_conn_total 1042353
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2020580
telemt_me_endpoint_quarantine_total 372
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 390
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10833
telemt_desync_full_logged_total 3750
telemt_desync_suppressed_total 7083
telemt_desync_frames_bucket_total{bucket="1_2"} 1984
telemt_desync_frames_bucket_total{bucket="3_10"} 4160
telemt_desync_frames_bucket_total{bucket="gt_10"} 4689
telemt_pool_swap_total 54
telemt_pool_force_close_total 1593
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 145
telemt_me_draining_writers_reap_progress_total 18675
telemt_me_writer_removed_unexpected_total 760
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1635
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17827
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17082
telemt_me_writer_teardown_success_total{mode="normal"} 19462
telemt_me_writer_teardown_noop_total 18677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38139
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.508147
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38139
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 145
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 894
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2024049
telemt_user_connections_current{user="hello"} 1864
telemt_user_octets_from_client{user="hello"} 55558538124 (51.74 GB)
telemt_user_octets_to_client{user="hello"} 862444983818 (803.21 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 902
telemt_user_unique_ips_recent_window{user="hello"} 288
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 30984.7 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219854
telemt_connections_bad_total 1809
telemt_connections_current 342
telemt_connections_me_current 342
telemt_handshake_timeouts_total 5906
telemt_upstream_connect_attempt_total 15039
telemt_upstream_connect_success_total 15003
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 15037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 343
telemt_me_reconnect_success_total 200
telemt_me_reader_eof_total 204
telemt_me_idle_close_by_peer_total 204
telemt_me_route_drop_no_conn_total 60776
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194433
telemt_me_endpoint_quarantine_total 300
telemt_me_single_endpoint_shadow_rotate_total 271
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1111
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 822
telemt_desync_frames_bucket_total{bucket="1_2"} 408
telemt_desync_frames_bucket_total{bucket="3_10"} 418
telemt_desync_frames_bucket_total{bucket="gt_10"} 285
telemt_pool_swap_total 34
telemt_pool_force_close_total 758
telemt_me_writer_close_signal_drop_total 25
telemt_me_draining_writers_reap_progress_total 13586
telemt_me_writer_removed_unexpected_total 197
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 865
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12925
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 756
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12828
telemt_me_writer_teardown_success_total{mode="normal"} 13790
telemt_me_writer_teardown_noop_total 13586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27376
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.089895
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27376
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 25
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 181
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 194097
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 3359056760 (3.13 GB)
telemt_user_octets_to_client{user="hello"} 118432296292 (110.30 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 113182.0 (31h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7509089
telemt_connections_bad_total 756044
telemt_connections_current 2207
telemt_connections_me_current 2207
telemt_handshake_timeouts_total 214264
telemt_upstream_connect_attempt_total 44620
telemt_upstream_connect_success_total 44458
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 44583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_reconnect_attempts_total 1641
telemt_me_reconnect_success_total 874
telemt_me_reader_eof_total 861
telemt_me_idle_close_by_peer_total 861
telemt_me_route_drop_no_conn_total 2152145
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5595688
telemt_me_endpoint_quarantine_total 806
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 871
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
telemt_desync_total 21926
telemt_desync_full_logged_total 7198
telemt_desync_suppressed_total 14728
telemt_desync_frames_bucket_total{bucket="1_2"} 5499
telemt_desync_frames_bucket_total{bucket="3_10"} 7944
telemt_desync_frames_bucket_total{bucket="gt_10"} 8483
telemt_pool_swap_total 125
telemt_pool_force_close_total 3335
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 40262
telemt_me_writer_removed_unexpected_total 829
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3136
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37977
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3247
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36927
telemt_me_writer_teardown_success_total{mode="normal"} 41113
telemt_me_writer_teardown_noop_total 40264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81377
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.720313
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81377
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 782
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 5570575
telemt_user_connections_current{user="hello"} 2207
telemt_user_octets_from_client{user="hello"} 110997088040 (103.37 GB)
telemt_user_octets_to_client{user="hello"} 2596344082848 (2.36 TB)
telemt_user_unique_ips_current{user="hello"} 1016
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 113178.6 (31h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6504981
telemt_connections_bad_total 638647
telemt_connections_current 2194
telemt_connections_me_current 2194
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 175809
telemt_upstream_connect_attempt_total 60427
telemt_upstream_connect_success_total 59976
telemt_upstream_connect_fail_total 392
telemt_upstream_connect_attempts_per_request{bucket="1"} 60368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24045
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 392
telemt_me_reconnect_attempts_total 5620
telemt_me_reconnect_success_total 1218
telemt_me_reader_eof_total 1101
telemt_me_idle_close_by_peer_total 1101
telemt_me_seq_mismatch_total 52
telemt_me_route_drop_no_conn_total 2204112
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4961599
telemt_me_endpoint_quarantine_total 888
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 866
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
telemt_me_writers_active_current 45
telemt_desync_total 20515
telemt_desync_full_logged_total 6851
telemt_desync_suppressed_total 13664
telemt_desync_frames_bucket_total{bucket="1_2"} 5239
telemt_desync_frames_bucket_total{bucket="3_10"} 7497
telemt_desync_frames_bucket_total{bucket="gt_10"} 7779
telemt_pool_swap_total 123
telemt_pool_force_close_total 3286
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 390
telemt_me_draining_writers_reap_progress_total 38817
telemt_me_writer_removed_unexpected_total 1113
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3684
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36301
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3063
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35531
telemt_me_writer_teardown_success_total{mode="normal"} 39985
telemt_me_writer_teardown_noop_total 38821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78806
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.198121
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78806
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 390
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 953
telemt_me_writer_restored_fallback_total 70
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4964455
telemt_user_connections_current{user="hello"} 2194
telemt_user_octets_from_client{user="hello"} 93714639617 (87.28 GB)
telemt_user_octets_to_client{user="hello"} 2123903076340 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 959
telemt_user_unique_ips_recent_window{user="hello"} 297
```