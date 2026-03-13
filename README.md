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

# Server Metrics 2026-03-13 23:39:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 144377.9 (40h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 585301
telemt_connections_bad_total 19495
telemt_handshake_timeouts_total 12836
telemt_upstream_connect_attempt_total 36750
telemt_upstream_connect_success_total 36567
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 36750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19705
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5160
telemt_me_reconnect_attempts_total 33631
telemt_me_reconnect_success_total 28964
telemt_me_reader_eof_total 30949
telemt_me_idle_close_by_peer_total 30948
telemt_me_route_drop_no_conn_total 192642
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502235
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1623
telemt_desync_full_logged_total 553
telemt_desync_suppressed_total 1070
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 608
telemt_desync_frames_bucket_total{bucket="gt_10"} 666
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 29432
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 28948
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 502130
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 15368016078 (14.31 GB)
telemt_user_octets_to_client{user="hello"} 249321053260 (232.20 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 144270.8 (40h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299442
telemt_connections_bad_total 2179
telemt_handshake_timeouts_total 1928
telemt_upstream_connect_attempt_total 141215
telemt_upstream_connect_success_total 140156
telemt_upstream_connect_fail_total 1059
telemt_upstream_connect_attempts_per_request{bucket="1"} 141215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31356
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1059
telemt_me_keepalive_timeout_total 3748
telemt_me_reconnect_attempts_total 152694
telemt_me_reconnect_success_total 29625
telemt_me_reader_eof_total 34251
telemt_me_idle_close_by_peer_total 34251
telemt_me_route_drop_no_conn_total 92071
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180801
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 37
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
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 33746
telemt_me_refill_failed_total 3840
telemt_me_writer_restored_same_endpoint_total 29608
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4121
telemt_user_connections_total{user="hello"} 283913
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 2982456803 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 89234579787 (83.11 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 144237.6 (40h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350187
telemt_connections_bad_total 2740
telemt_handshake_timeouts_total 31446
telemt_upstream_connect_attempt_total 38303
telemt_upstream_connect_success_total 38297
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 38303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2907
telemt_me_reconnect_attempts_total 32300
telemt_me_reconnect_success_total 31047
telemt_me_reader_eof_total 33342
telemt_me_idle_close_by_peer_total 33342
telemt_me_route_drop_no_conn_total 124080
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303717
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
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 31410
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 31027
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 363
telemt_user_connections_total{user="hello"} 303619
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 12534205016 (11.67 GB)
telemt_user_octets_to_client{user="hello"} 126072035716 (117.41 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 144210.1 (40h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451860
telemt_connections_bad_total 15359
telemt_handshake_timeouts_total 4250
telemt_upstream_connect_attempt_total 66050
telemt_upstream_connect_success_total 55639
telemt_upstream_connect_fail_total 10411
telemt_upstream_connect_attempts_per_request{bucket="1"} 66050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20954
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 315
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10411
telemt_me_keepalive_timeout_total 5025
telemt_me_reconnect_attempts_total 131874
telemt_me_reconnect_success_total 29397
telemt_me_reader_eof_total 33439
telemt_me_idle_close_by_peer_total 33431
telemt_me_route_drop_no_conn_total 158465
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 382110
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1672
telemt_desync_full_logged_total 491
telemt_desync_suppressed_total 1181
telemt_desync_frames_bucket_total{bucket="1_2"} 391
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 32963
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 29387
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3566
telemt_user_connections_total{user="hello"} 400952
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 9020843331 (8.40 GB)
telemt_user_octets_to_client{user="hello"} 153115701252 (142.60 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 94381.8 (26h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158297
telemt_connections_bad_total 23300
telemt_handshake_timeouts_total 1545
telemt_upstream_connect_attempt_total 34989
telemt_upstream_connect_success_total 34664
telemt_upstream_connect_fail_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 34989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 325
telemt_me_keepalive_timeout_total 1341
telemt_me_reconnect_attempts_total 38476
telemt_me_reconnect_success_total 25070
telemt_me_reader_eof_total 26798
telemt_me_idle_close_by_peer_total 26798
telemt_me_route_drop_no_conn_total 47902
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123793
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
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 25729
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 25052
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 659
telemt_user_connections_total{user="hello"} 128648
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 1579086253 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 61409812743 (57.19 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 144166.2 (40h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 857832
telemt_connections_bad_total 27313
telemt_handshake_timeouts_total 25200
telemt_upstream_connect_attempt_total 29810
telemt_upstream_connect_success_total 29649
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 29810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 3400
telemt_me_reconnect_attempts_total 27144
telemt_me_reconnect_success_total 22480
telemt_me_reader_eof_total 24099
telemt_me_idle_close_by_peer_total 24096
telemt_me_route_drop_no_conn_total 408990
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 800901
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 22920
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22473
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 773753
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 13308144324 (12.39 GB)
telemt_user_octets_to_client{user="hello"} 394896486884 (367.78 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 30
```