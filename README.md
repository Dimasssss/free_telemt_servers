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

# Server Metrics 2026-03-18 06:32:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 128834.2 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1610051
telemt_connections_bad_total 10700
telemt_handshake_timeouts_total 36452
telemt_upstream_connect_attempt_total 27948
telemt_upstream_connect_success_total 27427
telemt_upstream_connect_fail_total 521
telemt_upstream_connect_attempts_per_request{bucket="1"} 27948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 521
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 35864
telemt_me_reconnect_success_total 18709
telemt_me_reader_eof_total 20278
telemt_me_idle_close_by_peer_total 20277
telemt_me_route_drop_no_conn_total 631365
telemt_me_route_drop_channel_closed_total 176
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1379366
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8377
telemt_desync_full_logged_total 2524
telemt_desync_suppressed_total 5853
telemt_desync_frames_bucket_total{bucket="1_2"} 2187
telemt_desync_frames_bucket_total{bucket="3_10"} 3223
telemt_desync_frames_bucket_total{bucket="gt_10"} 2967
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19525
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18687
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 816
telemt_user_connections_total{user="hello"} 1373616
telemt_user_connections_current{user="hello"} 1123
telemt_user_octets_from_client{user="hello"} 32457839751 (30.23 GB)
telemt_user_octets_to_client{user="hello"} 492492836355 (458.67 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 129085.5 (35h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1716476
telemt_connections_bad_total 84617
telemt_handshake_timeouts_total 55321
telemt_upstream_connect_attempt_total 471418
telemt_upstream_connect_success_total 469780
telemt_upstream_connect_fail_total 1638
telemt_upstream_connect_attempts_per_request{bucket="1"} 471418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1638
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 127166
telemt_me_reconnect_success_total 20433
telemt_me_reader_eof_total 22746
telemt_me_idle_close_by_peer_total 22733
telemt_me_route_drop_no_conn_total 458103
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1053379
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4858
telemt_desync_full_logged_total 1695
telemt_desync_suppressed_total 3163
telemt_desync_frames_bucket_total{bucket="1_2"} 934
telemt_desync_frames_bucket_total{bucket="3_10"} 1965
telemt_desync_frames_bucket_total{bucket="gt_10"} 1959
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22067
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20415
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1634
telemt_user_connections_total{user="hello"} 1495659
telemt_user_connections_current{user="hello"} 2223
telemt_user_octets_from_client{user="hello"} 21972566761 (20.46 GB)
telemt_user_octets_to_client{user="hello"} 583469329838 (543.40 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 685
telemt_user_unique_ips_recent_window{user="hello"} 287
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 128861.6 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1211247
telemt_connections_bad_total 80127
telemt_handshake_timeouts_total 31019
telemt_upstream_connect_attempt_total 29222
telemt_upstream_connect_success_total 29057
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 29222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15605
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 43293
telemt_me_reconnect_success_total 22586
telemt_me_reader_eof_total 24542
telemt_me_idle_close_by_peer_total 24535
telemt_me_route_drop_no_conn_total 408180
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 916153
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3151
telemt_desync_full_logged_total 1017
telemt_desync_suppressed_total 2134
telemt_desync_frames_bucket_total{bucket="1_2"} 832
telemt_desync_frames_bucket_total{bucket="3_10"} 1218
telemt_desync_frames_bucket_total{bucket="gt_10"} 1101
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 23539
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22574
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 953
telemt_user_connections_total{user="hello"} 914229
telemt_user_connections_current{user="hello"} 1522
telemt_user_octets_from_client{user="hello"} 47429361024 (44.17 GB)
telemt_user_octets_to_client{user="hello"} 446971240428 (416.27 GB)
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 128920.8 (35h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1610203
telemt_connections_bad_total 82837
telemt_handshake_timeouts_total 28379
telemt_upstream_connect_attempt_total 92306
telemt_upstream_connect_success_total 89853
telemt_upstream_connect_fail_total 2453
telemt_upstream_connect_attempts_per_request{bucket="1"} 92306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2453
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 39083
telemt_me_reconnect_success_total 18660
telemt_me_reader_eof_total 20460
telemt_me_idle_close_by_peer_total 20457
telemt_me_route_drop_no_conn_total 641213
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1318145
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5139
telemt_desync_full_logged_total 1653
telemt_desync_suppressed_total 3486
telemt_desync_frames_bucket_total{bucket="1_2"} 1216
telemt_desync_frames_bucket_total{bucket="3_10"} 2128
telemt_desync_frames_bucket_total{bucket="gt_10"} 1795
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 19643
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18640
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 983
telemt_user_connections_total{user="hello"} 1381398
telemt_user_connections_current{user="hello"} 2138
telemt_user_octets_from_client{user="hello"} 23352101434 (21.75 GB)
telemt_user_octets_to_client{user="hello"} 669820026234 (623.82 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 592
telemt_user_unique_ips_recent_window{user="hello"} 266
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 128892.9 (35h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1149449
telemt_connections_bad_total 106803
telemt_handshake_timeouts_total 12067
telemt_upstream_connect_attempt_total 49314
telemt_upstream_connect_success_total 48633
telemt_upstream_connect_fail_total 681
telemt_upstream_connect_attempts_per_request{bucket="1"} 49314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 427
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 681
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60699
telemt_me_reconnect_success_total 25727
telemt_me_reader_eof_total 27808
telemt_me_idle_close_by_peer_total 27805
telemt_me_route_drop_no_conn_total 370699
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 946433
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4095
telemt_desync_full_logged_total 1256
telemt_desync_suppressed_total 2839
telemt_desync_frames_bucket_total{bucket="1_2"} 1133
telemt_desync_frames_bucket_total{bucket="3_10"} 1578
telemt_desync_frames_bucket_total{bucket="gt_10"} 1384
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27217
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25719
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1490
telemt_user_connections_total{user="hello"} 962858
telemt_user_connections_current{user="hello"} 1751
telemt_user_octets_from_client{user="hello"} 17850637920 (16.62 GB)
telemt_user_octets_to_client{user="hello"} 486269202408 (452.87 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 129054.0 (35h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1250299
telemt_connections_bad_total 132248
telemt_handshake_timeouts_total 10739
telemt_upstream_connect_attempt_total 25602
telemt_upstream_connect_success_total 25449
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 25602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13088
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 152
telemt_me_reconnect_attempts_total 30333
telemt_me_reconnect_success_total 19035
telemt_me_reader_eof_total 20619
telemt_me_idle_close_by_peer_total 20617
telemt_me_route_drop_no_conn_total 839831
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1222688
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2366
telemt_desync_full_logged_total 835
telemt_desync_suppressed_total 1531
telemt_desync_frames_bucket_total{bucket="1_2"} 528
telemt_desync_frames_bucket_total{bucket="3_10"} 908
telemt_desync_frames_bucket_total{bucket="gt_10"} 930
telemt_pool_swap_total 118
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19678
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19021
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 643
telemt_user_connections_total{user="hello"} 1031352
telemt_user_connections_current{user="hello"} 846
telemt_user_octets_from_client{user="hello"} 16294291128 (15.18 GB)
telemt_user_octets_to_client{user="hello"} 458590887420 (427.10 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 76821.0 (21h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634521
telemt_connections_bad_total 57821
telemt_handshake_timeouts_total 14298
telemt_upstream_connect_attempt_total 26183
telemt_upstream_connect_success_total 25908
telemt_upstream_connect_fail_total 275
telemt_upstream_connect_attempts_per_request{bucket="1"} 26183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 275
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 33550
telemt_me_reconnect_success_total 21934
telemt_me_reader_eof_total 23182
telemt_me_idle_close_by_peer_total 23182
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 158593
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470135
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2058
telemt_desync_full_logged_total 695
telemt_desync_suppressed_total 1363
telemt_desync_frames_bucket_total{bucket="1_2"} 335
telemt_desync_frames_bucket_total{bucket="3_10"} 909
telemt_desync_frames_bucket_total{bucket="gt_10"} 814
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22531
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21889
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 597
telemt_user_connections_total{user="hello"} 469885
telemt_user_connections_current{user="hello"} 1312
telemt_user_octets_from_client{user="hello"} 27377885205 (25.50 GB)
telemt_user_octets_to_client{user="hello"} 362133192210 (337.26 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 158
```