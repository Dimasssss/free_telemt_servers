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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 05:06:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 123644.1 (34h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1429369
telemt_connections_bad_total 10569
telemt_handshake_timeouts_total 34690
telemt_upstream_connect_attempt_total 27067
telemt_upstream_connect_success_total 26553
telemt_upstream_connect_fail_total 514
telemt_upstream_connect_attempts_per_request{bucket="1"} 27067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 514
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 35252
telemt_me_reconnect_success_total 18104
telemt_me_reader_eof_total 19636
telemt_me_idle_close_by_peer_total 19635
telemt_me_route_drop_no_conn_total 602762
telemt_me_route_drop_channel_closed_total 165
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1304089
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8059
telemt_desync_full_logged_total 2412
telemt_desync_suppressed_total 5647
telemt_desync_frames_bucket_total{bucket="1_2"} 2124
telemt_desync_frames_bucket_total{bucket="3_10"} 3086
telemt_desync_frames_bucket_total{bucket="gt_10"} 2849
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 18908
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18082
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 804
telemt_user_connections_total{user="hello"} 1298318
telemt_user_connections_current{user="hello"} 1018
telemt_user_octets_from_client{user="hello"} 29892738031 (27.84 GB)
telemt_user_octets_to_client{user="hello"} 459148850119 (427.62 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 374
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 123895.8 (34h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1543768
telemt_connections_bad_total 74191
telemt_handshake_timeouts_total 51245
telemt_upstream_connect_attempt_total 470499
telemt_upstream_connect_success_total 468874
telemt_upstream_connect_fail_total 1625
telemt_upstream_connect_attempts_per_request{bucket="1"} 470499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34572
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1625
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126520
telemt_me_reconnect_success_total 19792
telemt_me_reader_eof_total 22071
telemt_me_idle_close_by_peer_total 22058
telemt_me_route_drop_no_conn_total 403316
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 901528
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4047
telemt_desync_full_logged_total 1408
telemt_desync_suppressed_total 2639
telemt_desync_frames_bucket_total{bucket="1_2"} 789
telemt_desync_frames_bucket_total{bucket="3_10"} 1657
telemt_desync_frames_bucket_total{bucket="gt_10"} 1601
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 21415
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19774
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1623
telemt_user_connections_total{user="hello"} 1343841
telemt_user_connections_current{user="hello"} 1295
telemt_user_octets_from_client{user="hello"} 18327456789 (17.07 GB)
telemt_user_octets_to_client{user="hello"} 505111765974 (470.42 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 123671.8 (34h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 984681
telemt_connections_bad_total 69446
telemt_handshake_timeouts_total 27895
telemt_upstream_connect_attempt_total 28436
telemt_upstream_connect_success_total 28275
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 28436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15210
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42771
telemt_me_reconnect_success_total 22070
telemt_me_reader_eof_total 23988
telemt_me_idle_close_by_peer_total 23981
telemt_me_route_drop_no_conn_total 366341
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 805693
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2666
telemt_desync_full_logged_total 871
telemt_desync_suppressed_total 1795
telemt_desync_frames_bucket_total{bucket="1_2"} 736
telemt_desync_frames_bucket_total{bucket="3_10"} 1024
telemt_desync_frames_bucket_total{bucket="gt_10"} 906
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 23011
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22058
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 941
telemt_user_connections_total{user="hello"} 803800
telemt_user_connections_current{user="hello"} 1027
telemt_user_octets_from_client{user="hello"} 45444906264 (42.32 GB)
telemt_user_octets_to_client{user="hello"} 377811707192 (351.86 GB)
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 123731.3 (34h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1435891
telemt_connections_bad_total 70589
telemt_handshake_timeouts_total 24561
telemt_upstream_connect_attempt_total 91442
telemt_upstream_connect_success_total 89000
telemt_upstream_connect_fail_total 2442
telemt_upstream_connect_attempts_per_request{bucket="1"} 91442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2442
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38488
telemt_me_reconnect_success_total 18073
telemt_me_reader_eof_total 19835
telemt_me_idle_close_by_peer_total 19832
telemt_me_route_drop_no_conn_total 580589
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1169627
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4424
telemt_desync_full_logged_total 1451
telemt_desync_suppressed_total 2973
telemt_desync_frames_bucket_total{bucket="1_2"} 1075
telemt_desync_frames_bucket_total{bucket="3_10"} 1861
telemt_desync_frames_bucket_total{bucket="gt_10"} 1488
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 19046
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18053
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 973
telemt_user_connections_total{user="hello"} 1232930
telemt_user_connections_current{user="hello"} 1325
telemt_user_octets_from_client{user="hello"} 19310098954 (17.98 GB)
telemt_user_octets_to_client{user="hello"} 599921201878 (558.72 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 123702.9 (34h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 998944
telemt_connections_bad_total 102978
telemt_handshake_timeouts_total 9567
telemt_upstream_connect_attempt_total 48433
telemt_upstream_connect_success_total 47765
telemt_upstream_connect_fail_total 668
telemt_upstream_connect_attempts_per_request{bucket="1"} 48433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17828
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 668
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60092
telemt_me_reconnect_success_total 25126
telemt_me_reader_eof_total 27181
telemt_me_idle_close_by_peer_total 27178
telemt_me_route_drop_no_conn_total 320077
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 816025
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3660
telemt_desync_full_logged_total 1116
telemt_desync_suppressed_total 2544
telemt_desync_frames_bucket_total{bucket="1_2"} 1076
telemt_desync_frames_bucket_total{bucket="3_10"} 1425
telemt_desync_frames_bucket_total{bucket="gt_10"} 1159
telemt_pool_swap_total 65
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26605
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25118
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1479
telemt_user_connections_total{user="hello"} 832503
telemt_user_connections_current{user="hello"} 1170
telemt_user_octets_from_client{user="hello"} 15853459292 (14.76 GB)
telemt_user_octets_to_client{user="hello"} 422105212188 (393.12 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 123864.7 (34h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1190783
telemt_connections_bad_total 127284
telemt_handshake_timeouts_total 10419
telemt_upstream_connect_attempt_total 24662
telemt_upstream_connect_success_total 24518
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 24662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12630
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29661
telemt_me_reconnect_success_total 18367
telemt_me_reader_eof_total 19906
telemt_me_idle_close_by_peer_total 19904
telemt_me_route_drop_no_conn_total 818750
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1170988
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2217
telemt_desync_full_logged_total 776
telemt_desync_suppressed_total 1441
telemt_desync_frames_bucket_total{bucket="1_2"} 488
telemt_desync_frames_bucket_total{bucket="3_10"} 844
telemt_desync_frames_bucket_total{bucket="gt_10"} 885
telemt_pool_swap_total 112
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19004
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18353
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 979674
telemt_user_connections_current{user="hello"} 781
telemt_user_octets_from_client{user="hello"} 15556144716 (14.49 GB)
telemt_user_octets_to_client{user="hello"} 434070290436 (404.26 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 71631.2 (19h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533892
telemt_connections_bad_total 53692
telemt_handshake_timeouts_total 13140
telemt_upstream_connect_attempt_total 25279
telemt_upstream_connect_success_total 25018
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 25279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32919
telemt_me_reconnect_success_total 21306
telemt_me_reader_eof_total 22515
telemt_me_idle_close_by_peer_total 22515
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 130328
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384636
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1668
telemt_desync_full_logged_total 551
telemt_desync_suppressed_total 1117
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 747
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 49
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21894
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21263
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 384391
telemt_user_connections_current{user="hello"} 950
telemt_user_octets_from_client{user="hello"} 24301499669 (22.63 GB)
telemt_user_octets_to_client{user="hello"} 305538768250 (284.56 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 121
```