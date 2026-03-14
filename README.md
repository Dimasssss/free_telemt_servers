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

# Server Metrics 2026-03-14 05:36:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 165766.7 (46h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 639267
telemt_connections_bad_total 32298
telemt_handshake_timeouts_total 12987
telemt_upstream_connect_attempt_total 42331
telemt_upstream_connect_success_total 42115
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 42331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22737
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5571
telemt_me_reconnect_attempts_total 38139
telemt_me_reconnect_success_total 33451
telemt_me_reader_eof_total 35767
telemt_me_idle_close_by_peer_total 35766
telemt_me_route_drop_no_conn_total 208716
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541741
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1919
telemt_desync_full_logged_total 653
telemt_desync_suppressed_total 1266
telemt_desync_frames_bucket_total{bucket="1_2"} 414
telemt_desync_frames_bucket_total{bucket="3_10"} 700
telemt_desync_frames_bucket_total{bucket="gt_10"} 805
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 33960
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33431
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 509
telemt_user_connections_total{user="hello"} 541626
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 15928675202 (14.83 GB)
telemt_user_octets_to_client{user="hello"} 262053825192 (244.06 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 165660.5 (46h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322773
telemt_connections_bad_total 2288
telemt_handshake_timeouts_total 2344
telemt_upstream_connect_attempt_total 148356
telemt_upstream_connect_success_total 147142
telemt_upstream_connect_fail_total 1214
telemt_upstream_connect_attempts_per_request{bucket="1"} 148356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35499
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1214
telemt_me_keepalive_timeout_total 3898
telemt_me_reconnect_attempts_total 172392
telemt_me_reconnect_success_total 35581
telemt_me_reader_eof_total 40799
telemt_me_idle_close_by_peer_total 40799
telemt_me_route_drop_no_conn_total 103995
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202627
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 42
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
telemt_me_writer_removed_unexpected_total 40189
telemt_me_refill_failed_total 4269
telemt_me_writer_restored_same_endpoint_total 35564
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4608
telemt_user_connections_total{user="hello"} 305736
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 3178706663 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 99554355007 (92.72 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 165624.2 (46h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375348
telemt_connections_bad_total 2964
telemt_handshake_timeouts_total 34917
telemt_upstream_connect_attempt_total 43850
telemt_upstream_connect_success_total 43841
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 43850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3410
telemt_me_reconnect_attempts_total 36845
telemt_me_reconnect_success_total 35561
telemt_me_reader_eof_total 38230
telemt_me_idle_close_by_peer_total 38230
telemt_me_route_drop_no_conn_total 134907
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324445
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
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 35993
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 35540
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 324221
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 12861960336 (11.98 GB)
telemt_user_octets_to_client{user="hello"} 129203144096 (120.33 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 165599.8 (45h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 477145
telemt_connections_bad_total 15653
telemt_handshake_timeouts_total 4471
telemt_upstream_connect_attempt_total 73866
telemt_upstream_connect_success_total 63320
telemt_upstream_connect_fail_total 10546
telemt_upstream_connect_attempts_per_request{bucket="1"} 73866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10546
telemt_me_keepalive_timeout_total 5312
telemt_me_reconnect_attempts_total 142109
telemt_me_reconnect_success_total 36056
telemt_me_reader_eof_total 40500
telemt_me_idle_close_by_peer_total 40492
telemt_me_route_drop_no_conn_total 171423
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 405394
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1717
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 1211
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 664
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 39782
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 36046
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3726
telemt_user_connections_total{user="hello"} 424235
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 9235957707 (8.60 GB)
telemt_user_octets_to_client{user="hello"} 167465812832 (155.96 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 115771.1 (32h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189582
telemt_connections_bad_total 28071
telemt_handshake_timeouts_total 1658
telemt_upstream_connect_attempt_total 41385
telemt_upstream_connect_success_total 40999
telemt_upstream_connect_fail_total 386
telemt_upstream_connect_attempts_per_request{bucket="1"} 41385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 386
telemt_me_keepalive_timeout_total 2416
telemt_me_reconnect_attempts_total 43774
telemt_me_reconnect_success_total 30349
telemt_me_reader_eof_total 32491
telemt_me_idle_close_by_peer_total 32491
telemt_me_route_drop_no_conn_total 55992
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149783
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
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 31043
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30331
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 694
telemt_user_connections_total{user="hello"} 154532
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 2294000485 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 70018244703 (65.21 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 165555.8 (45h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 941958
telemt_connections_bad_total 32165
telemt_handshake_timeouts_total 25802
telemt_upstream_connect_attempt_total 34359
telemt_upstream_connect_success_total 34175
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 34359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 4608
telemt_me_reconnect_attempts_total 30676
telemt_me_reconnect_success_total 26002
telemt_me_reader_eof_total 27909
telemt_me_idle_close_by_peer_total 27906
telemt_me_route_drop_no_conn_total 445658
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 876201
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
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 26477
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25995
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 848860
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 14735638852 (13.72 GB)
telemt_user_octets_to_client{user="hello"} 433717721040 (403.93 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 59
```