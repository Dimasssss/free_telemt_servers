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

# Server Metrics 2026-03-13 21:17:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 135821.4 (37h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 568725
telemt_connections_bad_total 16246
telemt_handshake_timeouts_total 12738
telemt_upstream_connect_attempt_total 34430
telemt_upstream_connect_success_total 34257
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 34430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5095
telemt_me_reconnect_attempts_total 31754
telemt_me_reconnect_success_total 27098
telemt_me_reader_eof_total 28926
telemt_me_idle_close_by_peer_total 28925
telemt_me_route_drop_no_conn_total 187683
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 489745
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1556
telemt_desync_full_logged_total 528
telemt_desync_suppressed_total 1028
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 578
telemt_desync_frames_bucket_total{bucket="gt_10"} 642
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 27549
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 27082
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 489640
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 14721484362 (13.71 GB)
telemt_user_octets_to_client{user="hello"} 237228131384 (220.94 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 135715.1 (37h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288574
telemt_connections_bad_total 2136
telemt_handshake_timeouts_total 1902
telemt_upstream_connect_attempt_total 137707
telemt_upstream_connect_success_total 136713
telemt_upstream_connect_fail_total 994
telemt_upstream_connect_attempts_per_request{bucket="1"} 137707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2408
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 994
telemt_me_keepalive_timeout_total 3664
telemt_me_reconnect_attempts_total 143704
telemt_me_reconnect_success_total 26629
telemt_me_reader_eof_total 31022
telemt_me_idle_close_by_peer_total 31022
telemt_me_route_drop_no_conn_total 84374
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170650
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
telemt_me_writer_removed_unexpected_total 30534
telemt_me_refill_failed_total 3653
telemt_me_writer_restored_same_endpoint_total 26612
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3905
telemt_user_connections_total{user="hello"} 273763
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 2835841787 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 83166564691 (77.45 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 135678.9 (37h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335624
telemt_connections_bad_total 2657
telemt_handshake_timeouts_total 25950
telemt_upstream_connect_attempt_total 36092
telemt_upstream_connect_success_total 36087
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 36092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2838
telemt_me_reconnect_attempts_total 30525
telemt_me_reconnect_success_total 29282
telemt_me_reader_eof_total 31406
telemt_me_idle_close_by_peer_total 31406
telemt_me_route_drop_no_conn_total 119884
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295199
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
telemt_me_writer_removed_unexpected_total 29614
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 29262
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 295101
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 12293513344 (11.45 GB)
telemt_user_octets_to_client{user="hello"} 123040409820 (114.59 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 135654.3 (37h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441006
telemt_connections_bad_total 15256
telemt_handshake_timeouts_total 4207
telemt_upstream_connect_attempt_total 63829
telemt_upstream_connect_success_total 53495
telemt_upstream_connect_fail_total 10334
telemt_upstream_connect_attempts_per_request{bucket="1"} 63829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 300
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10334
telemt_me_keepalive_timeout_total 4768
telemt_me_reconnect_attempts_total 126135
telemt_me_reconnect_success_total 27700
telemt_me_reader_eof_total 31553
telemt_me_idle_close_by_peer_total 31546
telemt_me_route_drop_no_conn_total 153315
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 371753
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1564
telemt_desync_full_logged_total 460
telemt_desync_suppressed_total 1104
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 596
telemt_desync_frames_bucket_total{bucket="gt_10"} 597
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 31124
telemt_me_refill_failed_total 3070
telemt_me_writer_restored_same_endpoint_total 27690
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3424
telemt_user_connections_total{user="hello"} 390610
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 8821824315 (8.22 GB)
telemt_user_octets_to_client{user="hello"} 144460056756 (134.54 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 85825.9 (23h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146720
telemt_connections_bad_total 21059
telemt_handshake_timeouts_total 1524
telemt_upstream_connect_attempt_total 32234
telemt_upstream_connect_success_total 31926
telemt_upstream_connect_fail_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 32234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 308
telemt_me_keepalive_timeout_total 1289
telemt_me_reconnect_attempts_total 36130
telemt_me_reconnect_success_total 22735
telemt_me_reader_eof_total 24355
telemt_me_idle_close_by_peer_total 24355
telemt_me_route_drop_no_conn_total 45252
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114636
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
telemt_me_writer_removed_unexpected_total 23368
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22717
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 633
telemt_user_connections_total{user="hello"} 119530
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 1380926357 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 55082118015 (51.30 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 135610.4 (37h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 826068
telemt_connections_bad_total 27124
telemt_handshake_timeouts_total 25058
telemt_upstream_connect_attempt_total 27931
telemt_upstream_connect_success_total 27784
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 27931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14760
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 3117
telemt_me_reconnect_attempts_total 25713
telemt_me_reconnect_success_total 21062
telemt_me_reader_eof_total 22588
telemt_me_idle_close_by_peer_total 22585
telemt_me_route_drop_no_conn_total 393090
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 772811
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
telemt_me_writer_removed_unexpected_total 21488
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21055
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 426
telemt_user_connections_total{user="hello"} 745673
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 13018600592 (12.12 GB)
telemt_user_octets_to_client{user="hello"} 370148575508 (344.73 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 36
```