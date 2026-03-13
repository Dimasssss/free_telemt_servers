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

# Server Metrics 2026-03-13 20:51:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 134294.1 (37h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 564442
telemt_connections_bad_total 15643
telemt_handshake_timeouts_total 12662
telemt_upstream_connect_attempt_total 34106
telemt_upstream_connect_success_total 33933
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 34106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5065
telemt_me_reconnect_attempts_total 31473
telemt_me_reconnect_success_total 26820
telemt_me_reader_eof_total 28629
telemt_me_idle_close_by_peer_total 28628
telemt_me_route_drop_no_conn_total 186595
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 486378
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
telemt_me_writer_removed_unexpected_total 27266
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 26804
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 446
telemt_user_connections_total{user="hello"} 486273
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 14376942230 (13.39 GB)
telemt_user_octets_to_client{user="hello"} 234580851908 (218.47 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 134187.1 (37h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285763
telemt_connections_bad_total 2103
telemt_handshake_timeouts_total 1900
telemt_upstream_connect_attempt_total 136010
telemt_upstream_connect_success_total 135021
telemt_upstream_connect_fail_total 989
telemt_upstream_connect_attempts_per_request{bucket="1"} 136010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2397
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 989
telemt_me_keepalive_timeout_total 3651
telemt_me_reconnect_attempts_total 142168
telemt_me_reconnect_success_total 26471
telemt_me_reader_eof_total 30818
telemt_me_idle_close_by_peer_total 30818
telemt_me_route_drop_no_conn_total 84031
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169416
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
telemt_me_writer_removed_unexpected_total 30332
telemt_me_refill_failed_total 3610
telemt_me_writer_restored_same_endpoint_total 26454
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3861
telemt_user_connections_total{user="hello"} 271065
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 2820389432 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 82381677639 (76.72 GB)
telemt_user_msgs_from_client{user="hello"} 1663513
telemt_user_msgs_to_client{user="hello"} 9247698
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 134151.2 (37h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 332594
telemt_connections_bad_total 2650
telemt_handshake_timeouts_total 24970
telemt_upstream_connect_attempt_total 35589
telemt_upstream_connect_success_total 35584
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 35589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2821
telemt_me_reconnect_attempts_total 30097
telemt_me_reconnect_success_total 28857
telemt_me_reader_eof_total 30955
telemt_me_idle_close_by_peer_total 30955
telemt_me_route_drop_no_conn_total 119091
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293288
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
telemt_me_writer_removed_unexpected_total 29184
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 28837
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 293189
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 11930079972 (11.11 GB)
telemt_user_octets_to_client{user="hello"} 122444228920 (114.04 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 134126.3 (37h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 438387
telemt_connections_bad_total 15240
telemt_handshake_timeouts_total 4191
telemt_upstream_connect_attempt_total 63583
telemt_upstream_connect_success_total 53264
telemt_upstream_connect_fail_total 10319
telemt_upstream_connect_attempts_per_request{bucket="1"} 63583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19731
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 300
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10319
telemt_me_keepalive_timeout_total 4766
telemt_me_reconnect_attempts_total 123275
telemt_me_reconnect_success_total 27560
telemt_me_reader_eof_total 31327
telemt_me_idle_close_by_peer_total 31320
telemt_me_route_drop_no_conn_total 152298
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 369225
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
telemt_me_writer_removed_unexpected_total 30898
telemt_me_refill_failed_total 2985
telemt_me_writer_restored_same_endpoint_total 27550
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3338
telemt_user_connections_total{user="hello"} 388082
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 8750889235 (8.15 GB)
telemt_user_octets_to_client{user="hello"} 143043552448 (133.22 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 84297.8 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144202
telemt_connections_bad_total 20088
telemt_handshake_timeouts_total 1520
telemt_upstream_connect_attempt_total 31845
telemt_upstream_connect_success_total 31539
telemt_upstream_connect_fail_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 31845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 306
telemt_me_keepalive_timeout_total 1284
telemt_me_reconnect_attempts_total 35829
telemt_me_reconnect_success_total 22435
telemt_me_reader_eof_total 24032
telemt_me_idle_close_by_peer_total 24032
telemt_me_route_drop_no_conn_total 44627
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113155
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
telemt_me_writer_removed_unexpected_total 23064
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22417
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 629
telemt_user_connections_total{user="hello"} 118049
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 1372198521 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 53762892955 (50.07 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 134082.3 (37h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 818227
telemt_connections_bad_total 25295
telemt_handshake_timeouts_total 25042
telemt_upstream_connect_attempt_total 27616
telemt_upstream_connect_success_total 27470
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 27616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14596
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 3096
telemt_me_reconnect_attempts_total 25485
telemt_me_reconnect_success_total 20835
telemt_me_reader_eof_total 22343
telemt_me_idle_close_by_peer_total 22340
telemt_me_route_drop_no_conn_total 389964
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 767078
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
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 21259
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20828
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 424
telemt_user_connections_total{user="hello"} 739940
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 12944499860 (12.06 GB)
telemt_user_octets_to_client{user="hello"} 368018236880 (342.74 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 35
```