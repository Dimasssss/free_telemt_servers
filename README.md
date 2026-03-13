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

# Server Metrics 2026-03-13 00:13:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 59998.4 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255298
telemt_connections_bad_total 2753
telemt_handshake_timeouts_total 5276
telemt_upstream_connect_attempt_total 15075
telemt_upstream_connect_success_total 15009
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 15075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8332
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1494
telemt_me_reconnect_attempts_total 15452
telemt_me_reconnect_success_total 11981
telemt_me_reader_eof_total 12772
telemt_me_idle_close_by_peer_total 12771
telemt_me_route_drop_no_conn_total 79463
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211297
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 714
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12224
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 11965
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 211065
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 3885053796 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 107969740092 (100.55 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 59891.4 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117369
telemt_connections_bad_total 651
telemt_handshake_timeouts_total 946
telemt_upstream_connect_attempt_total 34071
telemt_upstream_connect_success_total 33676
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 34071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 500
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_keepalive_timeout_total 422
telemt_me_reconnect_attempts_total 56033
telemt_me_reconnect_success_total 14161
telemt_me_reader_eof_total 15845
telemt_me_idle_close_by_peer_total 15845
telemt_me_route_drop_no_conn_total 42342
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94904
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 15570
telemt_me_refill_failed_total 1307
telemt_me_writer_restored_same_endpoint_total 14146
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1409
telemt_user_connections_total{user="hello"} 111406
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 1217393836 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 34399509587 (32.04 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 59854.9 (16h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143016
telemt_connections_bad_total 1665
telemt_handshake_timeouts_total 2248
telemt_upstream_connect_attempt_total 16450
telemt_upstream_connect_success_total 16448
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 16450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8725
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 350
telemt_me_reconnect_attempts_total 14544
telemt_me_reconnect_success_total 13393
telemt_me_reader_eof_total 14309
telemt_me_idle_close_by_peer_total 14309
telemt_me_route_drop_no_conn_total 54124
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133757
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 13561
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 13373
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 133723
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 2619964488 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 62174396848 (57.90 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 59830.6 (16h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206142
telemt_connections_bad_total 13281
telemt_handshake_timeouts_total 1382
telemt_upstream_connect_attempt_total 28350
telemt_upstream_connect_success_total 18619
telemt_upstream_connect_fail_total 9731
telemt_upstream_connect_attempts_per_request{bucket="1"} 28350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9731
telemt_me_keepalive_timeout_total 3189
telemt_me_reconnect_attempts_total 45856
telemt_me_reconnect_success_total 12738
telemt_me_reader_eof_total 14226
telemt_me_idle_close_by_peer_total 14219
telemt_me_route_drop_no_conn_total 73520
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170067
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13965
telemt_me_refill_failed_total 1031
telemt_me_writer_restored_same_endpoint_total 12728
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1227
telemt_user_connections_total{user="hello"} 172821
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 3000102026 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 71021050545 (66.14 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 10002.2 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8831
telemt_connections_bad_total 1850
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 3167
telemt_upstream_connect_success_total 3135
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 3167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2599
telemt_me_reconnect_success_total 2594
telemt_me_reader_eof_total 2751
telemt_me_idle_close_by_peer_total 2751
telemt_me_route_drop_no_conn_total 2681
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6646
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2607
telemt_me_writer_restored_same_endpoint_total 2578
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 6646
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 23602520 (22.51 MB)
telemt_user_octets_to_client{user="hello"} 2250330972 (2.10 GB)
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 59787.0 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341096
telemt_connections_bad_total 5294
telemt_handshake_timeouts_total 2552
telemt_upstream_connect_attempt_total 12623
telemt_upstream_connect_success_total 12553
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 12623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1293
telemt_me_reconnect_attempts_total 13172
telemt_me_reconnect_success_total 9556
telemt_me_reader_eof_total 10251
telemt_me_idle_close_by_peer_total 10249
telemt_me_route_drop_no_conn_total 152833
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 335091
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 294
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9785
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 9549
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 323391
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 5550366664 (5.17 GB)
telemt_user_octets_to_client{user="hello"} 174250091184 (162.28 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 20
```