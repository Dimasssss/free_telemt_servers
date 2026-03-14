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

# Server Metrics 2026-03-14 01:21:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 150490.0 (41h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 595784
telemt_connections_bad_total 21649
telemt_handshake_timeouts_total 12872
telemt_upstream_connect_attempt_total 38320
telemt_upstream_connect_success_total 38130
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 38320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5482
telemt_me_reconnect_attempts_total 34888
telemt_me_reconnect_success_total 30215
telemt_me_reader_eof_total 32281
telemt_me_idle_close_by_peer_total 32280
telemt_me_route_drop_no_conn_total 195579
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 510288
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1651
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 1084
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 622
telemt_desync_frames_bucket_total{bucket="gt_10"} 675
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 30694
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 30199
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 479
telemt_user_connections_total{user="hello"} 510183
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 15530287190 (14.46 GB)
telemt_user_octets_to_client{user="hello"} 251659291356 (234.38 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 150383.3 (41h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305357
telemt_connections_bad_total 2236
telemt_handshake_timeouts_total 1938
telemt_upstream_connect_attempt_total 142879
telemt_upstream_connect_success_total 141770
telemt_upstream_connect_fail_total 1108
telemt_upstream_connect_attempts_per_request{bucket="1"} 142878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1108
telemt_me_keepalive_timeout_total 3790
telemt_me_reconnect_attempts_total 161892
telemt_me_reconnect_success_total 30947
telemt_me_reader_eof_total 35831
telemt_me_idle_close_by_peer_total 35831
telemt_me_route_drop_no_conn_total 95633
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186373
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 39
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
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 35326
telemt_me_refill_failed_total 4086
telemt_me_writer_restored_same_endpoint_total 30930
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4379
telemt_user_connections_total{user="hello"} 289485
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 3030143331 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 90410952787 (84.20 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 150346.7 (41h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357683
telemt_connections_bad_total 2823
telemt_handshake_timeouts_total 33211
telemt_upstream_connect_attempt_total 39877
telemt_upstream_connect_success_total 39871
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 39877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3259
telemt_me_reconnect_attempts_total 33596
telemt_me_reconnect_success_total 32333
telemt_me_reader_eof_total 34732
telemt_me_idle_close_by_peer_total 34732
telemt_me_route_drop_no_conn_total 126890
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309169
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
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 32716
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 32313
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 309065
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 12608888300 (11.74 GB)
telemt_user_octets_to_client{user="hello"} 126782053236 (118.07 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 150322.4 (41h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 458926
telemt_connections_bad_total 15368
telemt_handshake_timeouts_total 4321
telemt_upstream_connect_attempt_total 68180
telemt_upstream_connect_success_total 57736
telemt_upstream_connect_fail_total 10444
telemt_upstream_connect_attempts_per_request{bucket="1"} 68180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 317
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10444
telemt_me_keepalive_timeout_total 5065
telemt_me_reconnect_attempts_total 136206
telemt_me_reconnect_success_total 31228
telemt_me_reader_eof_total 35415
telemt_me_idle_close_by_peer_total 35407
telemt_me_route_drop_no_conn_total 162004
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388885
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 646
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 34885
telemt_me_refill_failed_total 3274
telemt_me_writer_restored_same_endpoint_total 31218
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3657
telemt_user_connections_total{user="hello"} 407727
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 9060414039 (8.44 GB)
telemt_user_octets_to_client{user="hello"} 155383234108 (144.71 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 100493.9 (27h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167820
telemt_connections_bad_total 24519
telemt_handshake_timeouts_total 1553
telemt_upstream_connect_attempt_total 36916
telemt_upstream_connect_success_total 36579
telemt_upstream_connect_fail_total 337
telemt_upstream_connect_attempts_per_request{bucket="1"} 36916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17825
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 337
telemt_me_keepalive_timeout_total 1374
telemt_me_reconnect_attempts_total 40089
telemt_me_reconnect_success_total 26677
telemt_me_reader_eof_total 28529
telemt_me_idle_close_by_peer_total 28529
telemt_me_route_drop_no_conn_total 50045
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131981
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 27338
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 26659
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 661
telemt_user_connections_total{user="hello"} 136796
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 1842962197 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 64195980903 (59.79 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 150278.4 (41h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 878055
telemt_connections_bad_total 27475
telemt_handshake_timeouts_total 25322
telemt_upstream_connect_attempt_total 30955
telemt_upstream_connect_success_total 30789
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 30955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 3415
telemt_me_reconnect_attempts_total 28025
telemt_me_reconnect_success_total 23360
telemt_me_reader_eof_total 25033
telemt_me_idle_close_by_peer_total 25030
telemt_me_route_drop_no_conn_total 418043
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 820470
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 706
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 23809
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23353
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 793226
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 14118984984 (13.15 GB)
telemt_user_octets_to_client{user="hello"} 405168043040 (377.34 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 29
```