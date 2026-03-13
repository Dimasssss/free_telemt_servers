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

# Server Metrics 2026-03-13 08:04:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 88250.6 (24h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340787
telemt_connections_bad_total 3169
telemt_handshake_timeouts_total 7523
telemt_upstream_connect_attempt_total 22112
telemt_upstream_connect_success_total 22011
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 22112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1658
telemt_me_reconnect_attempts_total 21095
telemt_me_reconnect_success_total 17590
telemt_me_reader_eof_total 18811
telemt_me_idle_close_by_peer_total 18810
telemt_me_route_drop_no_conn_total 106487
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290422
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 969
telemt_desync_full_logged_total 359
telemt_desync_suppressed_total 610
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 17886
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17574
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 290115
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 4812704644 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 133922469932 (124.73 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 88143.0 (24h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155212
telemt_connections_bad_total 1482
telemt_handshake_timeouts_total 1196
telemt_upstream_connect_attempt_total 44968
telemt_upstream_connect_success_total 44360
telemt_upstream_connect_fail_total 608
telemt_upstream_connect_attempts_per_request{bucket="1"} 44968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 511
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 608
telemt_me_keepalive_timeout_total 677
telemt_me_reconnect_attempts_total 77471
telemt_me_reconnect_success_total 23476
telemt_me_reader_eof_total 25855
telemt_me_idle_close_by_peer_total 25855
telemt_me_route_drop_no_conn_total 58576
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130181
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 25354
telemt_me_refill_failed_total 1685
telemt_me_writer_restored_same_endpoint_total 23461
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1878
telemt_user_connections_total{user="hello"} 146673
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 1522863892 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 47017812823 (43.79 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 88106.8 (24h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187338
telemt_connections_bad_total 1981
telemt_handshake_timeouts_total 3097
telemt_upstream_connect_attempt_total 23896
telemt_upstream_connect_success_total 23894
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 569
telemt_me_reconnect_attempts_total 20647
telemt_me_reconnect_success_total 19468
telemt_me_reader_eof_total 20876
telemt_me_idle_close_by_peer_total 20876
telemt_me_route_drop_no_conn_total 72398
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175337
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 19680
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19448
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 175267
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 6627722408 (6.17 GB)
telemt_user_octets_to_client{user="hello"} 74879073620 (69.74 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 88082.2 (24h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272153
telemt_connections_bad_total 13643
telemt_handshake_timeouts_total 2030
telemt_upstream_connect_attempt_total 36609
telemt_upstream_connect_success_total 26656
telemt_upstream_connect_fail_total 9953
telemt_upstream_connect_attempts_per_request{bucket="1"} 36609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9953
telemt_me_keepalive_timeout_total 3377
telemt_me_reconnect_attempts_total 70954
telemt_me_reconnect_success_total 19410
telemt_me_reader_eof_total 21647
telemt_me_idle_close_by_peer_total 21640
telemt_me_route_drop_no_conn_total 97724
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230895
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 850
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 601
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 315
telemt_desync_frames_bucket_total{bucket="gt_10"} 321
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 21269
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 19400
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1859
telemt_user_connections_total{user="hello"} 233621
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 5246966598 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 88667944893 (82.58 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 38253.9 (10h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47344
telemt_connections_bad_total 7811
telemt_handshake_timeouts_total 408
telemt_upstream_connect_attempt_total 13045
telemt_upstream_connect_success_total 12911
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 13045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7240
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 308
telemt_me_reconnect_attempts_total 11959
telemt_me_reconnect_success_total 10990
telemt_me_reader_eof_total 11704
telemt_me_idle_close_by_peer_total 11704
telemt_me_route_drop_no_conn_total 14009
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37811
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 11114
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 10972
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 37810
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 271615492 (259.03 MB)
telemt_user_octets_to_client{user="hello"} 11205317336 (10.44 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 88038.7 (24h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 464793
telemt_connections_bad_total 13235
telemt_handshake_timeouts_total 3867
telemt_upstream_connect_attempt_total 18630
telemt_upstream_connect_success_total 18529
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1524
telemt_me_reconnect_attempts_total 17807
telemt_me_reconnect_success_total 14166
telemt_me_reader_eof_total 15214
telemt_me_idle_close_by_peer_total 15211
telemt_me_route_drop_no_conn_total 226356
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 451569
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 372
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 14459
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14159
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 431312
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 7957067576 (7.41 GB)
telemt_user_octets_to_client{user="hello"} 248355092692 (231.30 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 71
```