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

# Server Metrics 2026-03-13 20:56:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 134599.7 (37h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565237
telemt_connections_bad_total 15731
telemt_handshake_timeouts_total 12678
telemt_upstream_connect_attempt_total 34168
telemt_upstream_connect_success_total 33995
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 34168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5067
telemt_me_reconnect_attempts_total 31535
telemt_me_reconnect_success_total 26882
telemt_me_reader_eof_total 28691
telemt_me_idle_close_by_peer_total 28690
telemt_me_route_drop_no_conn_total 186890
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 487035
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1551
telemt_desync_full_logged_total 527
telemt_desync_suppressed_total 1024
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 574
telemt_desync_frames_bucket_total{bucket="gt_10"} 641
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 27328
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 26866
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 446
telemt_user_connections_total{user="hello"} 486930
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 14542515178 (13.54 GB)
telemt_user_octets_to_client{user="hello"} 234917037628 (218.78 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 134492.5 (37h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286494
telemt_connections_bad_total 2128
telemt_handshake_timeouts_total 1900
telemt_upstream_connect_attempt_total 136546
telemt_upstream_connect_success_total 135555
telemt_upstream_connect_fail_total 991
telemt_upstream_connect_attempts_per_request{bucket="1"} 136546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2401
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 991
telemt_me_keepalive_timeout_total 3663
telemt_me_reconnect_attempts_total 143551
telemt_me_reconnect_success_total 26478
telemt_me_reader_eof_total 30868
telemt_me_idle_close_by_peer_total 30868
telemt_me_route_drop_no_conn_total 84070
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169593
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 34
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 30382
telemt_me_refill_failed_total 3653
telemt_me_writer_restored_same_endpoint_total 26461
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3904
telemt_user_connections_total{user="hello"} 271743
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 2823185019 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 82497077356 (76.83 GB)
telemt_user_msgs_from_client{user="hello"} 1670395
telemt_user_msgs_to_client{user="hello"} 9292861
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 134456.6 (37h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 333264
telemt_connections_bad_total 2651
telemt_handshake_timeouts_total 25162
telemt_upstream_connect_attempt_total 35737
telemt_upstream_connect_success_total 35732
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 35737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2823
telemt_me_reconnect_attempts_total 30213
telemt_me_reconnect_success_total 28972
telemt_me_reader_eof_total 31071
telemt_me_idle_close_by_peer_total 31071
telemt_me_route_drop_no_conn_total 119335
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293741
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
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
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 29300
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 28952
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 328
telemt_user_connections_total{user="hello"} 293643
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 11953038336 (11.13 GB)
telemt_user_octets_to_client{user="hello"} 122583670680 (114.16 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 134431.8 (37h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 438880
telemt_connections_bad_total 15244
telemt_handshake_timeouts_total 4194
telemt_upstream_connect_attempt_total 63669
telemt_upstream_connect_success_total 53343
telemt_upstream_connect_fail_total 10326
telemt_upstream_connect_attempts_per_request{bucket="1"} 63669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 300
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10326
telemt_me_keepalive_timeout_total 4768
telemt_me_reconnect_attempts_total 124687
telemt_me_reconnect_success_total 27596
telemt_me_reader_eof_total 31406
telemt_me_idle_close_by_peer_total 31399
telemt_me_route_drop_no_conn_total 152464
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 369705
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1542
telemt_desync_full_logged_total 455
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 365
telemt_desync_frames_bucket_total{bucket="3_10"} 585
telemt_desync_frames_bucket_total{bucket="gt_10"} 592
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 30977
telemt_me_refill_failed_total 3028
telemt_me_writer_restored_same_endpoint_total 27586
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3381
telemt_user_connections_total{user="hello"} 388562
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 8763652907 (8.16 GB)
telemt_user_octets_to_client{user="hello"} 143165346204 (133.33 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 84603.3 (23h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144706
telemt_connections_bad_total 20271
telemt_handshake_timeouts_total 1520
telemt_upstream_connect_attempt_total 31882
telemt_upstream_connect_success_total 31576
telemt_upstream_connect_fail_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 31882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 306
telemt_me_keepalive_timeout_total 1284
telemt_me_reconnect_attempts_total 35866
telemt_me_reconnect_success_total 22472
telemt_me_reader_eof_total 24071
telemt_me_idle_close_by_peer_total 24071
telemt_me_route_drop_no_conn_total 44768
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113461
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 607
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 23103
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22454
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 631
telemt_user_connections_total{user="hello"} 118355
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 1374238709 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 53974789203 (50.27 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 134388.0 (37h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 819319
telemt_connections_bad_total 25362
telemt_handshake_timeouts_total 25050
telemt_upstream_connect_attempt_total 27716
telemt_upstream_connect_success_total 27570
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 27716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14643
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 3096
telemt_me_reconnect_attempts_total 25542
telemt_me_reconnect_success_total 20892
telemt_me_reader_eof_total 22407
telemt_me_idle_close_by_peer_total 22404
telemt_me_route_drop_no_conn_total 390602
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 768048
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 21316
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20885
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 424
telemt_user_connections_total{user="hello"} 740910
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 12954547820 (12.06 GB)
telemt_user_octets_to_client{user="hello"} 368478077584 (343.17 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 44
```