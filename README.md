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

# Server Metrics 2026-03-14 08:29:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 176155.4 (48h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 678013
telemt_connections_bad_total 32490
telemt_handshake_timeouts_total 13254
telemt_upstream_connect_attempt_total 44755
telemt_upstream_connect_success_total 44527
telemt_upstream_connect_fail_total 228
telemt_upstream_connect_attempts_per_request{bucket="1"} 44755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 228
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5746
telemt_me_reconnect_attempts_total 40075
telemt_me_reconnect_success_total 35379
telemt_me_reader_eof_total 37827
telemt_me_idle_close_by_peer_total 37826
telemt_me_route_drop_no_conn_total 224366
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 578666
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2235
telemt_desync_full_logged_total 758
telemt_desync_suppressed_total 1477
telemt_desync_frames_bucket_total{bucket="1_2"} 483
telemt_desync_frames_bucket_total{bucket="3_10"} 819
telemt_desync_frames_bucket_total{bucket="gt_10"} 933
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 35905
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35359
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 578549
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 16891146794 (15.73 GB)
telemt_user_octets_to_client{user="hello"} 277641395804 (258.57 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 176049.1 (48h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341534
telemt_connections_bad_total 2782
telemt_handshake_timeouts_total 3004
telemt_upstream_connect_attempt_total 152078
telemt_upstream_connect_success_total 150772
telemt_upstream_connect_fail_total 1306
telemt_upstream_connect_attempts_per_request{bucket="1"} 152078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1306
telemt_me_keepalive_timeout_total 5316
telemt_me_reconnect_attempts_total 179300
telemt_me_reconnect_success_total 38695
telemt_me_reader_eof_total 44139
telemt_me_idle_close_by_peer_total 44139
telemt_me_route_drop_no_conn_total 114762
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219103
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 43465
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 38678
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4770
telemt_user_connections_total{user="hello"} 322209
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 3324123631 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 104591703475 (97.41 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 176012.7 (48h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398670
telemt_connections_bad_total 3196
telemt_handshake_timeouts_total 35373
telemt_upstream_connect_attempt_total 46486
telemt_upstream_connect_success_total 46477
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 46486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25147
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3509
telemt_me_reconnect_attempts_total 38960
telemt_me_reconnect_success_total 37668
telemt_me_reader_eof_total 40492
telemt_me_idle_close_by_peer_total 40492
telemt_me_route_drop_no_conn_total 144134
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 346061
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 38125
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 37647
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 457
telemt_user_connections_total{user="hello"} 345822
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 13654495824 (12.72 GB)
telemt_user_octets_to_client{user="hello"} 144531070348 (134.61 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 175988.3 (48h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 501199
telemt_connections_bad_total 16282
telemt_handshake_timeouts_total 4578
telemt_upstream_connect_attempt_total 76941
telemt_upstream_connect_success_total 66315
telemt_upstream_connect_fail_total 10626
telemt_upstream_connect_attempts_per_request{bucket="1"} 76941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27015
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10626
telemt_me_keepalive_timeout_total 5482
telemt_me_reconnect_attempts_total 148358
telemt_me_reconnect_success_total 38519
telemt_me_reader_eof_total 43180
telemt_me_idle_close_by_peer_total 43172
telemt_me_route_drop_no_conn_total 181380
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 427882
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1862
telemt_desync_full_logged_total 553
telemt_desync_suppressed_total 1309
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 708
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 42389
telemt_me_refill_failed_total 3425
telemt_me_writer_restored_same_endpoint_total 38509
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3870
telemt_user_connections_total{user="hello"} 446761
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 9643599859 (8.98 GB)
telemt_user_octets_to_client{user="hello"} 184430982236 (171.76 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 126159.8 (35h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206902
telemt_connections_bad_total 31437
telemt_handshake_timeouts_total 1766
telemt_upstream_connect_attempt_total 44452
telemt_upstream_connect_success_total 44022
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 44452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_keepalive_timeout_total 2565
telemt_me_reconnect_attempts_total 46789
telemt_me_reconnect_success_total 32840
telemt_me_reader_eof_total 35122
telemt_me_idle_close_by_peer_total 35122
telemt_me_route_drop_no_conn_total 62086
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163148
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 33575
telemt_me_refill_failed_total 432
telemt_me_writer_restored_same_endpoint_total 32822
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 735
telemt_user_connections_total{user="hello"} 167908
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 2468429137 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 80416057867 (74.89 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 175944.6 (48h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1012014
telemt_connections_bad_total 36316
telemt_handshake_timeouts_total 26314
telemt_upstream_connect_attempt_total 36618
telemt_upstream_connect_success_total 36423
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 36618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19242
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 4756
telemt_me_reconnect_attempts_total 32401
telemt_me_reconnect_success_total 27718
telemt_me_reader_eof_total 29728
telemt_me_idle_close_by_peer_total 29725
telemt_me_route_drop_no_conn_total 475130
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 937977
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 787
telemt_desync_full_logged_total 257
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 262
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 28214
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27711
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 910609
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 15452924660 (14.39 GB)
telemt_user_octets_to_client{user="hello"} 453783547740 (422.62 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 69
```