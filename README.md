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

# Server Metrics 2026-03-13 13:53:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 109224.1 (30h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 450479
telemt_connections_bad_total 3215
telemt_handshake_timeouts_total 8502
telemt_upstream_connect_attempt_total 27576
telemt_upstream_connect_success_total 27446
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 27576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2410
telemt_me_reconnect_attempts_total 25495
telemt_me_reconnect_success_total 21966
telemt_me_reader_eof_total 23463
telemt_me_idle_close_by_peer_total 23462
telemt_me_route_drop_no_conn_total 144618
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393546
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1316
telemt_desync_full_logged_total 467
telemt_desync_suppressed_total 849
telemt_desync_frames_bucket_total{bucket="1_2"} 284
telemt_desync_frames_bucket_total{bucket="3_10"} 479
telemt_desync_frames_bucket_total{bucket="gt_10"} 553
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 22305
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21950
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 393127
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 7131831816 (6.64 GB)
telemt_user_octets_to_client{user="hello"} 180016670792 (167.65 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 109117.8 (30h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211117
telemt_connections_bad_total 1740
telemt_handshake_timeouts_total 1520
telemt_upstream_connect_attempt_total 70749
telemt_upstream_connect_success_total 70011
telemt_upstream_connect_fail_total 738
telemt_upstream_connect_attempts_per_request{bucket="1"} 70749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 657
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 738
telemt_me_keepalive_timeout_total 1396
telemt_me_reconnect_attempts_total 105257
telemt_me_reconnect_success_total 26013
telemt_me_reader_eof_total 29249
telemt_me_idle_close_by_peer_total 29249
telemt_me_route_drop_no_conn_total 79899
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161102
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 25
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28713
telemt_me_refill_failed_total 2472
telemt_me_writer_restored_same_endpoint_total 25996
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2700
telemt_user_connections_total{user="hello"} 199414
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 2019344590 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 64468984209 (60.04 GB)
telemt_user_msgs_from_client{user="hello"} 567834
telemt_user_msgs_to_client{user="hello"} 3969177
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 109081.6 (30h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256561
telemt_connections_bad_total 2081
telemt_handshake_timeouts_total 10429
telemt_upstream_connect_attempt_total 29358
telemt_upstream_connect_success_total 29354
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 29358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2279
telemt_me_reconnect_attempts_total 25052
telemt_me_reconnect_success_total 23837
telemt_me_reader_eof_total 25542
telemt_me_idle_close_by_peer_total 25542
telemt_me_route_drop_no_conn_total 93389
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234794
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 24095
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23817
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 234712
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 9468071980 (8.82 GB)
telemt_user_octets_to_client{user="hello"} 100814525848 (93.89 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 109057.0 (30h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354396
telemt_connections_bad_total 15037
telemt_handshake_timeouts_total 3424
telemt_upstream_connect_attempt_total 41319
telemt_upstream_connect_success_total 31201
telemt_upstream_connect_fail_total 10118
telemt_upstream_connect_attempts_per_request{bucket="1"} 41319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15210
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10118
telemt_me_keepalive_timeout_total 4128
telemt_me_reconnect_attempts_total 96506
telemt_me_reconnect_success_total 22678
telemt_me_reader_eof_total 25673
telemt_me_idle_close_by_peer_total 25666
telemt_me_route_drop_no_conn_total 127084
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305524
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1158
telemt_desync_full_logged_total 341
telemt_desync_suppressed_total 817
telemt_desync_frames_bucket_total{bucket="1_2"} 286
telemt_desync_frames_bucket_total{bucket="3_10"} 434
telemt_desync_frames_bucket_total{bucket="gt_10"} 438
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 25272
telemt_me_refill_failed_total 2302
telemt_me_writer_restored_same_endpoint_total 22668
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2594
telemt_user_connections_total{user="hello"} 308434
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 6672500406 (6.21 GB)
telemt_user_octets_to_client{user="hello"} 115164593249 (107.26 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 59228.5 (16h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88938
telemt_connections_bad_total 11962
telemt_handshake_timeouts_total 1207
telemt_upstream_connect_attempt_total 24699
telemt_upstream_connect_success_total 24502
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 24699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 1003
telemt_me_reconnect_attempts_total 26554
telemt_me_reconnect_success_total 16634
telemt_me_reader_eof_total 17852
telemt_me_idle_close_by_peer_total 17852
telemt_me_route_drop_no_conn_total 26492
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68029
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 187
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 17088
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 16616
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 72929
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 886814333 (845.73 MB)
telemt_user_octets_to_client{user="hello"} 21468233827 (19.99 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 109013.6 (30h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 636159
telemt_connections_bad_total 17982
telemt_handshake_timeouts_total 18501
telemt_upstream_connect_attempt_total 23006
telemt_upstream_connect_success_total 22888
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 23006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2509
telemt_me_reconnect_attempts_total 22070
telemt_me_reconnect_success_total 17446
telemt_me_reader_eof_total 18728
telemt_me_idle_close_by_peer_total 18725
telemt_me_route_drop_no_conn_total 308688
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 605293
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 472
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 17816
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17439
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 578240
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 10148637612 (9.45 GB)
telemt_user_octets_to_client{user="hello"} 307472916156 (286.36 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 60
```