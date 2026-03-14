# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
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

## rdp-onedash.ru
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

# Server Metrics 2026-03-14 12:58:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 192336.5 (53h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 764576
telemt_connections_bad_total 36470
telemt_handshake_timeouts_total 14588
telemt_upstream_connect_attempt_total 48701
telemt_upstream_connect_success_total 48459
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 48701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6352
telemt_me_reconnect_attempts_total 44272
telemt_me_reconnect_success_total 38501
telemt_me_reader_eof_total 41162
telemt_me_idle_close_by_peer_total 41161
telemt_me_route_drop_no_conn_total 250967
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 656011
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2862
telemt_desync_full_logged_total 954
telemt_desync_suppressed_total 1908
telemt_desync_frames_bucket_total{bucket="1_2"} 588
telemt_desync_frames_bucket_total{bucket="3_10"} 1079
telemt_desync_frames_bucket_total{bucket="gt_10"} 1195
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 39094
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 38481
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 593
telemt_user_connections_total{user="hello"} 655916
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 18086464626 (16.84 GB)
telemt_user_octets_to_client{user="hello"} 311754861660 (290.34 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 192229.7 (53h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377472
telemt_connections_bad_total 2881
telemt_handshake_timeouts_total 3379
telemt_upstream_connect_attempt_total 158838
telemt_upstream_connect_success_total 157424
telemt_upstream_connect_fail_total 1414
telemt_upstream_connect_attempts_per_request{bucket="1"} 158838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40749
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2537
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1414
telemt_me_keepalive_timeout_total 5733
telemt_me_reconnect_attempts_total 198139
telemt_me_reconnect_success_total 42735
telemt_me_reader_eof_total 48698
telemt_me_idle_close_by_peer_total 48698
telemt_me_route_drop_no_conn_total 130302
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250715
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 48010
telemt_me_refill_failed_total 4848
telemt_me_writer_restored_same_endpoint_total 42717
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5275
telemt_user_connections_total{user="hello"} 355608
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 3613549767 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 113928851042 (106.10 GB)
telemt_user_msgs_from_client{user="hello"} 1713995
telemt_user_msgs_to_client{user="hello"} 9567945
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 192193.2 (53h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 434073
telemt_connections_bad_total 3336
telemt_handshake_timeouts_total 36798
telemt_upstream_connect_attempt_total 51535
telemt_upstream_connect_success_total 51526
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 51535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4356
telemt_me_reconnect_attempts_total 43164
telemt_me_reconnect_success_total 41840
telemt_me_reader_eof_total 44910
telemt_me_idle_close_by_peer_total 44910
telemt_me_route_drop_no_conn_total 159437
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378313
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 42339
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 41819
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 499
telemt_user_connections_total{user="hello"} 378047
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 16260591922 (15.14 GB)
telemt_user_octets_to_client{user="hello"} 167959872583 (156.42 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 192168.8 (53h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 554494
telemt_connections_bad_total 16788
telemt_handshake_timeouts_total 5356
telemt_upstream_connect_attempt_total 81676
telemt_upstream_connect_success_total 70939
telemt_upstream_connect_fail_total 10737
telemt_upstream_connect_attempts_per_request{bucket="1"} 81676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29362
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 393
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10737
telemt_me_keepalive_timeout_total 5882
telemt_me_reconnect_attempts_total 161957
telemt_me_reconnect_success_total 42320
telemt_me_reader_eof_total 47391
telemt_me_idle_close_by_peer_total 47383
telemt_me_route_drop_no_conn_total 200221
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476061
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2225
telemt_desync_full_logged_total 656
telemt_desync_suppressed_total 1569
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 842
telemt_desync_frames_bucket_total{bucket="gt_10"} 862
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 46541
telemt_me_refill_failed_total 3730
telemt_me_writer_restored_same_endpoint_total 42310
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4221
telemt_user_connections_total{user="hello"} 494919
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 10413468983 (9.70 GB)
telemt_user_octets_to_client{user="hello"} 203966246696 (189.96 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 142340.4 (39h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243023
telemt_connections_bad_total 38915
telemt_handshake_timeouts_total 2242
telemt_upstream_connect_attempt_total 50025
telemt_upstream_connect_success_total 49516
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 50025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_timeout_total 3160
telemt_me_reconnect_attempts_total 58849
telemt_me_reconnect_success_total 37519
telemt_me_reader_eof_total 40208
telemt_me_idle_close_by_peer_total 40208
telemt_me_route_drop_no_conn_total 74274
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190417
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 874
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 668
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 329
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 38534
telemt_me_refill_failed_total 662
telemt_me_writer_restored_same_endpoint_total 37501
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 1015
telemt_user_connections_total{user="hello"} 195168
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 2799212637 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 89372943759 (83.24 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 192124.9 (53h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1124635
telemt_connections_bad_total 38047
telemt_handshake_timeouts_total 27453
telemt_upstream_connect_attempt_total 40018
telemt_upstream_connect_success_total 39809
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 40018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 5241
telemt_me_reconnect_attempts_total 34994
telemt_me_reconnect_success_total 30294
telemt_me_reader_eof_total 32473
telemt_me_idle_close_by_peer_total 32470
telemt_me_route_drop_no_conn_total 529873
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1043126
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 817
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 547
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 286
telemt_pool_swap_total 179
telemt_me_writer_removed_unexpected_total 30823
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 30287
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 1015746
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 21839685132 (20.34 GB)
telemt_user_octets_to_client{user="hello"} 515632961896 (480.22 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 66
```