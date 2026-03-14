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

# Server Metrics 2026-03-14 04:09:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 160574.1 (44h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 623993
telemt_connections_bad_total 31107
telemt_handshake_timeouts_total 12937
telemt_upstream_connect_attempt_total 41074
telemt_upstream_connect_success_total 40866
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 41074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5548
telemt_me_reconnect_attempts_total 37150
telemt_me_reconnect_success_total 32467
telemt_me_reader_eof_total 34699
telemt_me_idle_close_by_peer_total 34698
telemt_me_route_drop_no_conn_total 202685
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 528363
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1811
telemt_desync_full_logged_total 610
telemt_desync_suppressed_total 1201
telemt_desync_frames_bucket_total{bucket="1_2"} 385
telemt_desync_frames_bucket_total{bucket="3_10"} 669
telemt_desync_frames_bucket_total{bucket="gt_10"} 757
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 32967
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 32447
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 500
telemt_user_connections_total{user="hello"} 528252
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 15733078254 (14.65 GB)
telemt_user_octets_to_client{user="hello"} 257460658000 (239.78 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 160467.1 (44h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315310
telemt_connections_bad_total 2267
telemt_handshake_timeouts_total 2143
telemt_upstream_connect_attempt_total 146759
telemt_upstream_connect_success_total 145578
telemt_upstream_connect_fail_total 1181
telemt_upstream_connect_attempts_per_request{bucket="1"} 146759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1181
telemt_me_keepalive_timeout_total 3865
telemt_me_reconnect_attempts_total 169818
telemt_me_reconnect_success_total 34258
telemt_me_reader_eof_total 39388
telemt_me_idle_close_by_peer_total 39388
telemt_me_route_drop_no_conn_total 99565
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195686
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 41
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
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 38819
telemt_me_refill_failed_total 4230
telemt_me_writer_restored_same_endpoint_total 34241
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4561
telemt_user_connections_total{user="hello"} 298798
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 3118796159 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 96723443843 (90.08 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 160431.0 (44h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368122
telemt_connections_bad_total 2919
telemt_handshake_timeouts_total 34790
telemt_upstream_connect_attempt_total 42559
telemt_upstream_connect_success_total 42550
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 42559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23036
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3353
telemt_me_reconnect_attempts_total 35776
telemt_me_reconnect_success_total 34497
telemt_me_reader_eof_total 37081
telemt_me_idle_close_by_peer_total 37081
telemt_me_route_drop_no_conn_total 131599
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317658
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
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 34916
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 34476
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 317463
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 12677585388 (11.81 GB)
telemt_user_octets_to_client{user="hello"} 127956346880 (119.17 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 160406.3 (44h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469747
telemt_connections_bad_total 15548
telemt_handshake_timeouts_total 4401
telemt_upstream_connect_attempt_total 72285
telemt_upstream_connect_success_total 61777
telemt_upstream_connect_fail_total 10508
telemt_upstream_connect_attempts_per_request{bucket="1"} 72285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24562
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10508
telemt_me_keepalive_timeout_total 5166
telemt_me_reconnect_attempts_total 140781
telemt_me_reconnect_success_total 34735
telemt_me_reader_eof_total 39124
telemt_me_idle_close_by_peer_total 39116
telemt_me_route_drop_no_conn_total 167718
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398596
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1710
telemt_desync_full_logged_total 503
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 38448
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 34725
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3713
telemt_user_connections_total{user="hello"} 417431
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 9176523375 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 162786991408 (151.61 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 110577.8 (30h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182530
telemt_connections_bad_total 26368
telemt_handshake_timeouts_total 1638
telemt_upstream_connect_attempt_total 39926
telemt_upstream_connect_success_total 39557
telemt_upstream_connect_fail_total 369
telemt_upstream_connect_attempts_per_request{bucket="1"} 39926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19499
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 369
telemt_me_keepalive_timeout_total 2375
telemt_me_reconnect_attempts_total 42592
telemt_me_reconnect_success_total 29172
telemt_me_reader_eof_total 31215
telemt_me_idle_close_by_peer_total 31215
telemt_me_route_drop_no_conn_total 54014
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144598
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 29856
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 29154
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 684
telemt_user_connections_total{user="hello"} 149354
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 2217032965 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 68784641903 (64.06 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 160362.3 (44h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 913684
telemt_connections_bad_total 28167
telemt_handshake_timeouts_total 25481
telemt_upstream_connect_attempt_total 33362
telemt_upstream_connect_success_total 33183
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 33362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17594
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 4041
telemt_me_reconnect_attempts_total 29900
telemt_me_reconnect_success_total 25230
telemt_me_reader_eof_total 27077
telemt_me_idle_close_by_peer_total 27074
telemt_me_route_drop_no_conn_total 435079
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 853011
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
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 25697
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25223
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 467
telemt_user_connections_total{user="hello"} 825676
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 14397842476 (13.41 GB)
telemt_user_octets_to_client{user="hello"} 414984810260 (386.48 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 38
```