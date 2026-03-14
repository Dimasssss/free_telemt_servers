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

# Server Metrics 2026-03-14 06:06:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 167599.0 (46h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 644865
telemt_connections_bad_total 32306
telemt_handshake_timeouts_total 13007
telemt_upstream_connect_attempt_total 42710
telemt_upstream_connect_success_total 42494
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 42710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22947
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5605
telemt_me_reconnect_attempts_total 38432
telemt_me_reconnect_success_total 33743
telemt_me_reader_eof_total 36086
telemt_me_idle_close_by_peer_total 36085
telemt_me_route_drop_no_conn_total 211300
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547067
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1967
telemt_desync_full_logged_total 673
telemt_desync_suppressed_total 1294
telemt_desync_frames_bucket_total{bucket="1_2"} 425
telemt_desync_frames_bucket_total{bucket="3_10"} 720
telemt_desync_frames_bucket_total{bucket="gt_10"} 822
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 34256
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33723
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 513
telemt_user_connections_total{user="hello"} 546952
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 16023260354 (14.92 GB)
telemt_user_octets_to_client{user="hello"} 265545564024 (247.31 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 167491.9 (46h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325380
telemt_connections_bad_total 2289
telemt_handshake_timeouts_total 2382
telemt_upstream_connect_attempt_total 149289
telemt_upstream_connect_success_total 148049
telemt_upstream_connect_fail_total 1239
telemt_upstream_connect_attempts_per_request{bucket="1"} 149288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2420
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1239
telemt_me_keepalive_timeout_total 3969
telemt_me_reconnect_attempts_total 174365
telemt_me_reconnect_success_total 36401
telemt_me_reader_eof_total 41667
telemt_me_idle_close_by_peer_total 41667
telemt_me_route_drop_no_conn_total 105152
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205120
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
telemt_me_writer_removed_unexpected_total 41050
telemt_me_refill_failed_total 4305
telemt_me_writer_restored_same_endpoint_total 36384
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4649
telemt_user_connections_total{user="hello"} 308226
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 3191748051 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 100544117499 (93.64 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 167455.7 (46h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379003
telemt_connections_bad_total 2966
telemt_handshake_timeouts_total 34930
telemt_upstream_connect_attempt_total 44308
telemt_upstream_connect_success_total 44299
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 44308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3454
telemt_me_reconnect_attempts_total 37195
telemt_me_reconnect_success_total 35911
telemt_me_reader_eof_total 38611
telemt_me_idle_close_by_peer_total 38611
telemt_me_route_drop_no_conn_total 136589
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327973
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
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 36345
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 35890
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 434
telemt_user_connections_total{user="hello"} 327745
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 13354852748 (12.44 GB)
telemt_user_octets_to_client{user="hello"} 129990690396 (121.06 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 167431.4 (46h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 479896
telemt_connections_bad_total 15654
telemt_handshake_timeouts_total 4482
telemt_upstream_connect_attempt_total 74426
telemt_upstream_connect_success_total 63870
telemt_upstream_connect_fail_total 10556
telemt_upstream_connect_attempts_per_request{bucket="1"} 74426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25713
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 337
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10556
telemt_me_keepalive_timeout_total 5372
telemt_me_reconnect_attempts_total 142571
telemt_me_reconnect_success_total 36516
telemt_me_reader_eof_total 40986
telemt_me_idle_close_by_peer_total 40978
telemt_me_route_drop_no_conn_total 172968
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408033
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1740
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 1226
telemt_desync_frames_bucket_total{bucket="1_2"} 412
telemt_desync_frames_bucket_total{bucket="3_10"} 658
telemt_desync_frames_bucket_total{bucket="gt_10"} 670
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 40247
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 36506
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3731
telemt_user_connections_total{user="hello"} 426874
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 9261569371 (8.63 GB)
telemt_user_octets_to_client{user="hello"} 170143904948 (158.46 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 117602.7 (32h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192381
telemt_connections_bad_total 28511
telemt_handshake_timeouts_total 1666
telemt_upstream_connect_attempt_total 41879
telemt_upstream_connect_success_total 41484
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 41879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_keepalive_timeout_total 2447
telemt_me_reconnect_attempts_total 44173
telemt_me_reconnect_success_total 30748
telemt_me_reader_eof_total 32910
telemt_me_idle_close_by_peer_total 32910
telemt_me_route_drop_no_conn_total 56998
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152079
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 623
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 31450
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30730
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 702
telemt_user_connections_total{user="hello"} 156828
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 2351663133 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 71334949023 (66.44 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 167387.2 (46h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 955516
telemt_connections_bad_total 35992
telemt_handshake_timeouts_total 25899
telemt_upstream_connect_attempt_total 34726
telemt_upstream_connect_success_total 34539
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 34726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_timeout_total 4669
telemt_me_reconnect_attempts_total 30953
telemt_me_reconnect_success_total 26277
telemt_me_reader_eof_total 28203
telemt_me_idle_close_by_peer_total 28200
telemt_me_route_drop_no_conn_total 450445
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 885588
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
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 26757
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26270
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 480
telemt_user_connections_total{user="hello"} 858241
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 14862818072 (13.84 GB)
telemt_user_octets_to_client{user="hello"} 437321391896 (407.29 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 52
```