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

# Server Metrics 2026-03-13 21:37:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 137044.0 (38h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 571662
telemt_connections_bad_total 16591
telemt_handshake_timeouts_total 12768
telemt_upstream_connect_attempt_total 34791
telemt_upstream_connect_success_total 34616
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 34791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18594
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5109
telemt_me_reconnect_attempts_total 32027
telemt_me_reconnect_success_total 27371
telemt_me_reader_eof_total 29227
telemt_me_idle_close_by_peer_total 29226
telemt_me_route_drop_no_conn_total 188551
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 491995
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1574
telemt_desync_full_logged_total 535
telemt_desync_suppressed_total 1039
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 583
telemt_desync_frames_bucket_total{bucket="gt_10"} 651
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 27823
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 27355
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 491890
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 14756946186 (13.74 GB)
telemt_user_octets_to_client{user="hello"} 241063155528 (224.51 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 136936.5 (38h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290455
telemt_connections_bad_total 2136
telemt_handshake_timeouts_total 1906
telemt_upstream_connect_attempt_total 138190
telemt_upstream_connect_success_total 137184
telemt_upstream_connect_fail_total 1006
telemt_upstream_connect_attempts_per_request{bucket="1"} 138190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2409
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1006
telemt_me_keepalive_timeout_total 3668
telemt_me_reconnect_attempts_total 144088
telemt_me_reconnect_success_total 27013
telemt_me_reader_eof_total 31410
telemt_me_idle_close_by_peer_total 31410
telemt_me_route_drop_no_conn_total 85756
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172360
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 35
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
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 30922
telemt_me_refill_failed_total 3653
telemt_me_writer_restored_same_endpoint_total 26996
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3909
telemt_user_connections_total{user="hello"} 275473
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 2851685791 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 83806846755 (78.05 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 136900.3 (38h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338064
telemt_connections_bad_total 2658
telemt_handshake_timeouts_total 26722
telemt_upstream_connect_attempt_total 36424
telemt_upstream_connect_success_total 36419
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 36424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2845
telemt_me_reconnect_attempts_total 30771
telemt_me_reconnect_success_total 29526
telemt_me_reader_eof_total 31666
telemt_me_idle_close_by_peer_total 31666
telemt_me_route_drop_no_conn_total 120491
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296763
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
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 29862
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 29506
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 336
telemt_user_connections_total{user="hello"} 296664
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 12318924400 (11.47 GB)
telemt_user_octets_to_client{user="hello"} 123307427880 (114.84 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 136875.8 (38h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443277
telemt_connections_bad_total 15257
telemt_handshake_timeouts_total 4218
telemt_upstream_connect_attempt_total 64000
telemt_upstream_connect_success_total 53657
telemt_upstream_connect_fail_total 10343
telemt_upstream_connect_attempts_per_request{bucket="1"} 64000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 302
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10343
telemt_me_keepalive_timeout_total 4769
telemt_me_reconnect_attempts_total 127567
telemt_me_reconnect_success_total 27788
telemt_me_reader_eof_total 31684
telemt_me_idle_close_by_peer_total 31677
telemt_me_route_drop_no_conn_total 154137
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 373919
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1589
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 1119
telemt_desync_frames_bucket_total{bucket="1_2"} 377
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 31255
telemt_me_refill_failed_total 3112
telemt_me_writer_restored_same_endpoint_total 27778
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3467
telemt_user_connections_total{user="hello"} 392776
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 8875018163 (8.27 GB)
telemt_user_octets_to_client{user="hello"} 147838361408 (137.69 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 87047.2 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148312
telemt_connections_bad_total 21847
telemt_handshake_timeouts_total 1524
telemt_upstream_connect_attempt_total 32551
telemt_upstream_connect_success_total 32241
telemt_upstream_connect_fail_total 309
telemt_upstream_connect_attempts_per_request{bucket="1"} 32550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 309
telemt_me_keepalive_timeout_total 1292
telemt_me_reconnect_attempts_total 36403
telemt_me_reconnect_success_total 23007
telemt_me_reader_eof_total 24644
telemt_me_idle_close_by_peer_total 24644
telemt_me_route_drop_no_conn_total 45537
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115416
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 611
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 468
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 23644
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22989
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 120310
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 1387549177 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 56502509179 (52.62 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 136831.8 (38h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 831065
telemt_connections_bad_total 27126
telemt_handshake_timeouts_total 25079
telemt_upstream_connect_attempt_total 28138
telemt_upstream_connect_success_total 27990
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 28138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14867
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 3117
telemt_me_reconnect_attempts_total 25866
telemt_me_reconnect_success_total 21215
telemt_me_reader_eof_total 22750
telemt_me_idle_close_by_peer_total 22747
telemt_me_route_drop_no_conn_total 395408
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 777627
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 693
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 21643
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21208
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 750489
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 13066748684 (12.17 GB)
telemt_user_octets_to_client{user="hello"} 373927258804 (348.25 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 30
```