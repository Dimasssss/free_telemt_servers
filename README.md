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

# Server Metrics 2026-03-13 21:22:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 136126.2 (37h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 569502
telemt_connections_bad_total 16310
telemt_handshake_timeouts_total 12752
telemt_upstream_connect_attempt_total 34537
telemt_upstream_connect_success_total 34363
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 34537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18442
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5096
telemt_me_reconnect_attempts_total 31817
telemt_me_reconnect_success_total 27161
telemt_me_reader_eof_total 29000
telemt_me_idle_close_by_peer_total 28999
telemt_me_route_drop_no_conn_total 187847
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 490368
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1561
telemt_desync_full_logged_total 531
telemt_desync_suppressed_total 1030
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 579
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 27613
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 27145
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 490263
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 14731895718 (13.72 GB)
telemt_user_octets_to_client{user="hello"} 238100277820 (221.75 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 136020.0 (37h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288985
telemt_connections_bad_total 2136
telemt_handshake_timeouts_total 1902
telemt_upstream_connect_attempt_total 137794
telemt_upstream_connect_success_total 136795
telemt_upstream_connect_fail_total 999
telemt_upstream_connect_attempts_per_request{bucket="1"} 137794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2408
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 999
telemt_me_keepalive_timeout_total 3664
telemt_me_reconnect_attempts_total 143748
telemt_me_reconnect_success_total 26673
telemt_me_reader_eof_total 31066
telemt_me_idle_close_by_peer_total 31066
telemt_me_route_drop_no_conn_total 84483
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171055
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
telemt_me_writer_removed_unexpected_total 30578
telemt_me_refill_failed_total 3653
telemt_me_writer_restored_same_endpoint_total 26656
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3905
telemt_user_connections_total{user="hello"} 274168
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 2838495235 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 83340362451 (77.62 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 135983.8 (37h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336365
telemt_connections_bad_total 2657
telemt_handshake_timeouts_total 26142
telemt_upstream_connect_attempt_total 36175
telemt_upstream_connect_success_total 36170
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 36175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19423
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2839
telemt_me_reconnect_attempts_total 30567
telemt_me_reconnect_success_total 29324
telemt_me_reader_eof_total 31448
telemt_me_idle_close_by_peer_total 31448
telemt_me_route_drop_no_conn_total 120085
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295718
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
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 29656
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 29304
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 295620
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 12296670208 (11.45 GB)
telemt_user_octets_to_client{user="hello"} 123097045944 (114.64 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 135959.2 (37h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441503
telemt_connections_bad_total 15256
telemt_handshake_timeouts_total 4215
telemt_upstream_connect_attempt_total 63869
telemt_upstream_connect_success_total 53535
telemt_upstream_connect_fail_total 10334
telemt_upstream_connect_attempts_per_request{bucket="1"} 63869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19832
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 301
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10334
telemt_me_keepalive_timeout_total 4768
telemt_me_reconnect_attempts_total 126157
telemt_me_reconnect_success_total 27722
telemt_me_reader_eof_total 31576
telemt_me_idle_close_by_peer_total 31569
telemt_me_route_drop_no_conn_total 153472
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372216
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1571
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 1108
telemt_desync_frames_bucket_total{bucket="1_2"} 373
telemt_desync_frames_bucket_total{bucket="3_10"} 600
telemt_desync_frames_bucket_total{bucket="gt_10"} 598
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 31147
telemt_me_refill_failed_total 3070
telemt_me_writer_restored_same_endpoint_total 27712
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3425
telemt_user_connections_total{user="hello"} 391073
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 8838753111 (8.23 GB)
telemt_user_octets_to_client{user="hello"} 145642265180 (135.64 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 86130.8 (23h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147125
telemt_connections_bad_total 21270
telemt_handshake_timeouts_total 1524
telemt_upstream_connect_attempt_total 32298
telemt_upstream_connect_success_total 31990
telemt_upstream_connect_fail_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 32298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 308
telemt_me_keepalive_timeout_total 1289
telemt_me_reconnect_attempts_total 36194
telemt_me_reconnect_success_total 22799
telemt_me_reader_eof_total 24420
telemt_me_idle_close_by_peer_total 24420
telemt_me_route_drop_no_conn_total 45296
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114827
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 608
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 23433
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22781
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 119721
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 1381998301 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 55339315303 (51.54 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 135915.3 (37h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 827255
telemt_connections_bad_total 27124
telemt_handshake_timeouts_total 25060
telemt_upstream_connect_attempt_total 27957
telemt_upstream_connect_success_total 27810
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 27957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 3117
telemt_me_reconnect_attempts_total 25739
telemt_me_reconnect_success_total 21088
telemt_me_reader_eof_total 22616
telemt_me_idle_close_by_peer_total 22613
telemt_me_route_drop_no_conn_total 393554
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 773969
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
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 21516
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21081
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 746831
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 13028209132 (12.13 GB)
telemt_user_octets_to_client{user="hello"} 370644903688 (345.19 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 37
```