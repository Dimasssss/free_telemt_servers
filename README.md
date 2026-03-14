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

# Server Metrics 2026-03-14 06:27:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 168822.4 (46h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 648787
telemt_connections_bad_total 32326
telemt_handshake_timeouts_total 13043
telemt_upstream_connect_attempt_total 43001
telemt_upstream_connect_success_total 42784
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 43001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5633
telemt_me_reconnect_attempts_total 38679
telemt_me_reconnect_success_total 33989
telemt_me_reader_eof_total 36346
telemt_me_idle_close_by_peer_total 36345
telemt_me_route_drop_no_conn_total 213240
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 550810
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1999
telemt_desync_full_logged_total 684
telemt_desync_suppressed_total 1315
telemt_desync_frames_bucket_total{bucket="1_2"} 435
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 833
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 34503
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33969
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 550695
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 16092912958 (14.99 GB)
telemt_user_octets_to_client{user="hello"} 266946413884 (248.61 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 168714.8 (46h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327148
telemt_connections_bad_total 2320
telemt_handshake_timeouts_total 2419
telemt_upstream_connect_attempt_total 149689
telemt_upstream_connect_success_total 148434
telemt_upstream_connect_fail_total 1255
telemt_upstream_connect_attempts_per_request{bucket="1"} 149689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1255
telemt_me_keepalive_timeout_total 3990
telemt_me_reconnect_attempts_total 177305
telemt_me_reconnect_success_total 36716
telemt_me_reader_eof_total 42067
telemt_me_idle_close_by_peer_total 42067
telemt_me_route_drop_no_conn_total 106259
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206741
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
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 41450
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 36699
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4734
telemt_user_connections_total{user="hello"} 309848
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 3234934215 (3.01 GB)
telemt_user_octets_to_client{user="hello"} 101074589323 (94.13 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 168678.5 (46h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381713
telemt_connections_bad_total 2970
telemt_handshake_timeouts_total 34949
telemt_upstream_connect_attempt_total 44619
telemt_upstream_connect_success_total 44610
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 44619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3469
telemt_me_reconnect_attempts_total 37443
telemt_me_reconnect_success_total 36158
telemt_me_reader_eof_total 38884
telemt_me_idle_close_by_peer_total 38884
telemt_me_route_drop_no_conn_total 137667
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330547
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
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 36594
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 36137
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 330320
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 13404687564 (12.48 GB)
telemt_user_octets_to_client{user="hello"} 130924717120 (121.93 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 168653.9 (46h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 482498
telemt_connections_bad_total 15660
telemt_handshake_timeouts_total 4492
telemt_upstream_connect_attempt_total 74937
telemt_upstream_connect_success_total 64370
telemt_upstream_connect_fail_total 10567
telemt_upstream_connect_attempts_per_request{bucket="1"} 74937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25980
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10567
telemt_me_keepalive_timeout_total 5389
telemt_me_reconnect_attempts_total 142987
telemt_me_reconnect_success_total 36928
telemt_me_reader_eof_total 41427
telemt_me_idle_close_by_peer_total 41419
telemt_me_route_drop_no_conn_total 174047
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 410470
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1762
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 669
telemt_desync_frames_bucket_total{bucket="gt_10"} 674
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 40663
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 36918
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3735
telemt_user_connections_total{user="hello"} 429315
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 9292050163 (8.65 GB)
telemt_user_octets_to_client{user="hello"} 174274201096 (162.31 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 118825.5 (33h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193968
telemt_connections_bad_total 28744
telemt_handshake_timeouts_total 1667
telemt_upstream_connect_attempt_total 42196
telemt_upstream_connect_success_total 41799
telemt_upstream_connect_fail_total 397
telemt_upstream_connect_attempts_per_request{bucket="1"} 42196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 397
telemt_me_keepalive_timeout_total 2453
telemt_me_reconnect_attempts_total 44444
telemt_me_reconnect_success_total 31017
telemt_me_reader_eof_total 33199
telemt_me_idle_close_by_peer_total 33199
telemt_me_route_drop_no_conn_total 57557
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153384
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 625
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 477
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 31720
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30999
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 703
telemt_user_connections_total{user="hello"} 158133
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 2360356893 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 71879027975 (66.94 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 168610.0 (46h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 962445
telemt_connections_bad_total 36032
telemt_handshake_timeouts_total 26017
telemt_upstream_connect_attempt_total 35026
telemt_upstream_connect_success_total 34838
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 35026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 4694
telemt_me_reconnect_attempts_total 31166
telemt_me_reconnect_success_total 26489
telemt_me_reader_eof_total 28438
telemt_me_idle_close_by_peer_total 28435
telemt_me_route_drop_no_conn_total 454001
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 892141
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
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 26971
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26482
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 864791
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 14920914056 (13.90 GB)
telemt_user_octets_to_client{user="hello"} 438309248180 (408.21 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 58
```