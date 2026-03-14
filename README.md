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

# Server Metrics 2026-03-14 03:54:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 159655.9 (44h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 621168
telemt_connections_bad_total 30504
telemt_handshake_timeouts_total 12936
telemt_upstream_connect_attempt_total 40851
telemt_upstream_connect_success_total 40646
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 40851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21930
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5547
telemt_me_reconnect_attempts_total 36973
telemt_me_reconnect_success_total 32290
telemt_me_reader_eof_total 34509
telemt_me_idle_close_by_peer_total 34508
telemt_me_route_drop_no_conn_total 201874
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 526209
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1794
telemt_desync_full_logged_total 607
telemt_desync_suppressed_total 1187
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 666
telemt_desync_frames_bucket_total{bucket="gt_10"} 750
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 32788
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 32270
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 526101
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 15715451950 (14.64 GB)
telemt_user_octets_to_client{user="hello"} 257028074980 (239.38 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 159549.0 (44h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313950
telemt_connections_bad_total 2266
telemt_handshake_timeouts_total 1945
telemt_upstream_connect_attempt_total 146438
telemt_upstream_connect_success_total 145266
telemt_upstream_connect_fail_total 1172
telemt_upstream_connect_attempts_per_request{bucket="1"} 146438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1172
telemt_me_keepalive_timeout_total 3857
telemt_me_reconnect_attempts_total 168301
telemt_me_reconnect_success_total 33988
telemt_me_reader_eof_total 39076
telemt_me_idle_close_by_peer_total 39076
telemt_me_route_drop_no_conn_total 99055
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194610
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
telemt_me_writer_removed_unexpected_total 38507
telemt_me_refill_failed_total 4191
telemt_me_writer_restored_same_endpoint_total 33971
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4519
telemt_user_connections_total{user="hello"} 297722
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 3113318415 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 96553713707 (89.92 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 159512.6 (44h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366945
telemt_connections_bad_total 2910
telemt_handshake_timeouts_total 34786
telemt_upstream_connect_attempt_total 42304
telemt_upstream_connect_success_total 42298
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 42304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3327
telemt_me_reconnect_attempts_total 35567
telemt_me_reconnect_success_total 34292
telemt_me_reader_eof_total 36857
telemt_me_idle_close_by_peer_total 36857
telemt_me_route_drop_no_conn_total 131006
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316531
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
telemt_me_writer_removed_unexpected_total 34692
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 34271
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 400
telemt_user_connections_total{user="hello"} 316345
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 12672007884 (11.80 GB)
telemt_user_octets_to_client{user="hello"} 127741832832 (118.97 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 159488.1 (44h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 468408
telemt_connections_bad_total 15546
telemt_handshake_timeouts_total 4401
telemt_upstream_connect_attempt_total 72025
telemt_upstream_connect_success_total 61521
telemt_upstream_connect_fail_total 10504
telemt_upstream_connect_attempts_per_request{bucket="1"} 72025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24427
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10504
telemt_me_keepalive_timeout_total 5142
telemt_me_reconnect_attempts_total 140568
telemt_me_reconnect_success_total 34523
telemt_me_reader_eof_total 38889
telemt_me_idle_close_by_peer_total 38881
telemt_me_route_drop_no_conn_total 166903
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 397379
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
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
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 38233
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 34513
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3710
telemt_user_connections_total{user="hello"} 416209
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 9147212903 (8.52 GB)
telemt_user_octets_to_client{user="hello"} 162029157680 (150.90 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 109659.7 (30h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181484
telemt_connections_bad_total 26203
telemt_handshake_timeouts_total 1602
telemt_upstream_connect_attempt_total 39693
telemt_upstream_connect_success_total 39325
telemt_upstream_connect_fail_total 368
telemt_upstream_connect_attempts_per_request{bucket="1"} 39693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 368
telemt_me_keepalive_timeout_total 2372
telemt_me_reconnect_attempts_total 42403
telemt_me_reconnect_success_total 28983
telemt_me_reader_eof_total 31011
telemt_me_idle_close_by_peer_total 31011
telemt_me_route_drop_no_conn_total 53843
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143784
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
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 29665
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 28965
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 682
telemt_user_connections_total{user="hello"} 148543
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 2201283349 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 68722532799 (64.00 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 159444.1 (44h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 908778
telemt_connections_bad_total 28137
telemt_handshake_timeouts_total 25433
telemt_upstream_connect_attempt_total 33165
telemt_upstream_connect_success_total 32991
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 33165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 3511
telemt_me_reconnect_attempts_total 29750
telemt_me_reconnect_success_total 25081
telemt_me_reader_eof_total 26883
telemt_me_idle_close_by_peer_total 26880
telemt_me_route_drop_no_conn_total 432994
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 849558
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 759
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 25546
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25074
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 822223
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 14367949492 (13.38 GB)
telemt_user_octets_to_client{user="hello"} 413627741600 (385.22 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 32
```