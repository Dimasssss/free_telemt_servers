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

# Server Metrics 2026-03-12 14:45:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 25950.5 (7h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137872
telemt_connections_bad_total 1422
telemt_handshake_timeouts_total 4550
telemt_upstream_connect_attempt_total 6277
telemt_upstream_connect_success_total 6253
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 6277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 4956
telemt_me_reconnect_success_total 4924
telemt_me_reader_eof_total 5180
telemt_me_idle_close_by_peer_total 5179
telemt_me_route_drop_no_conn_total 39214
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120285
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 568
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 358
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4969
telemt_me_writer_restored_same_endpoint_total 4908
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 120247
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 2020300644 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 44540913916 (41.48 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 25843.4 (7h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57552
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 367
telemt_upstream_connect_attempt_total 7910
telemt_upstream_connect_success_total 7736
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 7910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 170
telemt_me_reconnect_attempts_total 23347
telemt_me_reconnect_success_total 6425
telemt_me_reader_eof_total 7073
telemt_me_idle_close_by_peer_total 7073
telemt_me_route_drop_no_conn_total 25478
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54915
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 6994
telemt_me_refill_failed_total 528
telemt_me_writer_restored_same_endpoint_total 6410
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 569
telemt_user_connections_total{user="hello"} 54907
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 620385416 (591.65 MB)
telemt_user_octets_to_client{user="hello"} 15859427220 (14.77 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 25807.0 (7h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78856
telemt_connections_bad_total 1428
telemt_handshake_timeouts_total 1525
telemt_upstream_connect_attempt_total 6967
telemt_upstream_connect_success_total 6967
telemt_upstream_connect_attempts_per_request{bucket="1"} 6967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3582
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 5666
telemt_me_reconnect_success_total 5617
telemt_me_reader_eof_total 5943
telemt_me_idle_close_by_peer_total 5943
telemt_me_route_drop_no_conn_total 27774
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72575
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5660
telemt_me_writer_restored_same_endpoint_total 5597
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 72549
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 1944641488 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 40533296392 (37.75 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 25782.6 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100047
telemt_connections_bad_total 2960
telemt_handshake_timeouts_total 740
telemt_upstream_connect_attempt_total 6597
telemt_upstream_connect_success_total 6422
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 6597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 20924
telemt_me_reconnect_success_total 5096
telemt_me_reader_eof_total 5723
telemt_me_idle_close_by_peer_total 5723
telemt_me_route_drop_no_conn_total 36948
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90746
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 295
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 198
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5648
telemt_me_refill_failed_total 493
telemt_me_writer_restored_same_endpoint_total 5088
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 552
telemt_user_connections_total{user="hello"} 90629
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 1654780152 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 37835111960 (35.24 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 25752.1 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59375
telemt_connections_bad_total 5001
telemt_handshake_timeouts_total 1049
telemt_upstream_connect_attempt_total 24023
telemt_upstream_connect_success_total 23704
telemt_upstream_connect_fail_total 319
telemt_upstream_connect_attempts_per_request{bucket="1"} 24023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4426
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 319
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 34207
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4634
telemt_me_idle_close_by_peer_total 4634
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12445
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33234
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4659
telemt_me_refill_failed_total 955
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 975
telemt_user_connections_total{user="hello"} 51929
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 428859457 (408.99 MB)
telemt_user_octets_to_client{user="hello"} 12842421614 (11.96 GB)
telemt_user_msgs_from_client{user="hello"} 265988
telemt_user_msgs_to_client{user="hello"} 768152
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 25739.5 (7h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158089
telemt_connections_bad_total 799
telemt_handshake_timeouts_total 1222
telemt_upstream_connect_attempt_total 5257
telemt_upstream_connect_success_total 5230
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 5257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 3948
telemt_me_reconnect_success_total 3917
telemt_me_reader_eof_total 4128
telemt_me_idle_close_by_peer_total 4128
telemt_me_route_drop_no_conn_total 61722
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151241
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 234
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3963
telemt_me_writer_restored_same_endpoint_total 3910
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 151207
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 3001537668 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 66330152952 (61.77 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 69
```