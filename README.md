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

# Server Metrics 2026-03-14 05:20:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 164851.0 (45h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 636760
telemt_connections_bad_total 32287
telemt_handshake_timeouts_total 12974
telemt_upstream_connect_attempt_total 42103
telemt_upstream_connect_success_total 41887
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 42103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5565
telemt_me_reconnect_attempts_total 37956
telemt_me_reconnect_success_total 33270
telemt_me_reader_eof_total 35568
telemt_me_idle_close_by_peer_total 35567
telemt_me_route_drop_no_conn_total 207492
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 539332
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1907
telemt_desync_full_logged_total 646
telemt_desync_suppressed_total 1261
telemt_desync_frames_bucket_total{bucket="1_2"} 411
telemt_desync_frames_bucket_total{bucket="3_10"} 698
telemt_desync_frames_bucket_total{bucket="gt_10"} 798
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 33778
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33250
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 508
telemt_user_connections_total{user="hello"} 539216
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 15876219446 (14.79 GB)
telemt_user_octets_to_client{user="hello"} 260933946372 (243.01 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 164744.8 (45h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321632
telemt_connections_bad_total 2280
telemt_handshake_timeouts_total 2335
telemt_upstream_connect_attempt_total 147960
telemt_upstream_connect_success_total 146755
telemt_upstream_connect_fail_total 1205
telemt_upstream_connect_attempts_per_request{bucket="1"} 147960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1205
telemt_me_keepalive_timeout_total 3890
telemt_me_reconnect_attempts_total 172062
telemt_me_reconnect_success_total 35251
telemt_me_reader_eof_total 40467
telemt_me_idle_close_by_peer_total 40467
telemt_me_route_drop_no_conn_total 102861
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201540
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 42
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
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 39857
telemt_me_refill_failed_total 4269
telemt_me_writer_restored_same_endpoint_total 35234
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4606
telemt_user_connections_total{user="hello"} 304649
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 3160703323 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 98753281699 (91.97 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 164708.4 (45h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373823
telemt_connections_bad_total 2957
telemt_handshake_timeouts_total 34914
telemt_upstream_connect_attempt_total 43601
telemt_upstream_connect_success_total 43592
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 43601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23629
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3406
telemt_me_reconnect_attempts_total 36646
telemt_me_reconnect_success_total 35363
telemt_me_reader_eof_total 38014
telemt_me_idle_close_by_peer_total 38014
telemt_me_route_drop_no_conn_total 134261
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322976
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 35792
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 35342
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 322753
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 12724042676 (11.85 GB)
telemt_user_octets_to_client{user="hello"} 128899424912 (120.05 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 164683.9 (45h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475642
telemt_connections_bad_total 15640
telemt_handshake_timeouts_total 4414
telemt_upstream_connect_attempt_total 73538
telemt_upstream_connect_success_total 63003
telemt_upstream_connect_fail_total 10535
telemt_upstream_connect_attempts_per_request{bucket="1"} 73538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10535
telemt_me_keepalive_timeout_total 5297
telemt_me_reconnect_attempts_total 141835
telemt_me_reconnect_success_total 35783
telemt_me_reader_eof_total 40225
telemt_me_idle_close_by_peer_total 40217
telemt_me_route_drop_no_conn_total 170939
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 404046
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1716
telemt_desync_full_logged_total 505
telemt_desync_suppressed_total 1211
telemt_desync_frames_bucket_total{bucket="1_2"} 404
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 664
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 39507
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 35773
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3724
telemt_user_connections_total{user="hello"} 422887
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 9224915771 (8.59 GB)
telemt_user_octets_to_client{user="hello"} 166238219908 (154.82 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 114855.6 (31h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187961
telemt_connections_bad_total 27381
telemt_handshake_timeouts_total 1658
telemt_upstream_connect_attempt_total 41158
telemt_upstream_connect_success_total 40776
telemt_upstream_connect_fail_total 382
telemt_upstream_connect_attempts_per_request{bucket="1"} 41158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 382
telemt_me_keepalive_timeout_total 2413
telemt_me_reconnect_attempts_total 43594
telemt_me_reconnect_success_total 30169
telemt_me_reader_eof_total 32295
telemt_me_idle_close_by_peer_total 32295
telemt_me_route_drop_no_conn_total 55672
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148869
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 30859
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30151
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 690
telemt_user_connections_total{user="hello"} 153622
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 2289566553 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 69779049183 (64.99 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 164640.0 (45h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 936969
telemt_connections_bad_total 32071
telemt_handshake_timeouts_total 25798
telemt_upstream_connect_attempt_total 34197
telemt_upstream_connect_success_total 34013
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 34197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 4593
telemt_me_reconnect_attempts_total 30557
telemt_me_reconnect_success_total 25884
telemt_me_reader_eof_total 27780
telemt_me_idle_close_by_peer_total 27777
telemt_me_route_drop_no_conn_total 443463
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 871541
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 26358
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25877
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 474
telemt_user_connections_total{user="hello"} 844201
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 14697182764 (13.69 GB)
telemt_user_octets_to_client{user="hello"} 429938737076 (400.41 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 39
```