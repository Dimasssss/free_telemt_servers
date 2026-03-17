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

# Server Metrics 2026-03-17 23:45:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 104398.4 (28h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1241053
telemt_connections_bad_total 9046
telemt_handshake_timeouts_total 32304
telemt_upstream_connect_attempt_total 23435
telemt_upstream_connect_success_total 22940
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 23435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32589
telemt_me_reconnect_success_total 15454
telemt_me_reader_eof_total 16781
telemt_me_idle_close_by_peer_total 16780
telemt_me_route_drop_no_conn_total 549595
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1140049
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7480
telemt_desync_full_logged_total 2183
telemt_desync_suppressed_total 5297
telemt_desync_frames_bucket_total{bucket="1_2"} 1999
telemt_desync_frames_bucket_total{bucket="3_10"} 2837
telemt_desync_frames_bucket_total{bucket="gt_10"} 2644
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 16215
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15432
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 1134270
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 22589436203 (21.04 GB)
telemt_user_octets_to_client{user="hello"} 409347742319 (381.23 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 104649.7 (29h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1315100
telemt_connections_bad_total 61184
telemt_handshake_timeouts_total 45463
telemt_upstream_connect_attempt_total 459062
telemt_upstream_connect_success_total 458145
telemt_upstream_connect_fail_total 917
telemt_upstream_connect_attempts_per_request{bucket="1"} 459062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31410
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 917
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 59069
telemt_me_reconnect_success_total 15911
telemt_me_reader_eof_total 17958
telemt_me_idle_close_by_peer_total 17958
telemt_me_route_drop_no_conn_total 342338
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 705225
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3223
telemt_desync_full_logged_total 1058
telemt_desync_suppressed_total 2165
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 1320
telemt_desync_frames_bucket_total{bucket="gt_10"} 1276
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 17455
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15895
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1544
telemt_user_connections_total{user="hello"} 1141653
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 15669189058 (14.59 GB)
telemt_user_octets_to_client{user="hello"} 391748901366 (364.84 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 104425.6 (29h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 776183
telemt_connections_bad_total 49323
telemt_handshake_timeouts_total 23745
telemt_upstream_connect_attempt_total 24555
telemt_upstream_connect_success_total 24412
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 24555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13123
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39849
telemt_me_reconnect_success_total 19168
telemt_me_reader_eof_total 20889
telemt_me_idle_close_by_peer_total 20882
telemt_me_route_drop_no_conn_total 316175
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 659967
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2135
telemt_desync_full_logged_total 695
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 703
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 20077
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19156
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 909
telemt_user_connections_total{user="hello"} 658203
telemt_user_connections_current{user="hello"} 470
telemt_user_octets_from_client{user="hello"} 31990273776 (29.79 GB)
telemt_user_octets_to_client{user="hello"} 290956106544 (270.97 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 104485.2 (29h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1263169
telemt_connections_bad_total 49645
telemt_handshake_timeouts_total 21666
telemt_upstream_connect_attempt_total 84189
telemt_upstream_connect_success_total 83751
telemt_upstream_connect_fail_total 438
telemt_upstream_connect_attempts_per_request{bucket="1"} 84189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12829
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 438
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35480
telemt_me_reconnect_success_total 15152
telemt_me_reader_eof_total 16681
telemt_me_idle_close_by_peer_total 16679
telemt_me_route_drop_no_conn_total 519666
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1030609
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3885
telemt_desync_full_logged_total 1282
telemt_desync_suppressed_total 2603
telemt_desync_frames_bucket_total{bucket="1_2"} 950
telemt_desync_frames_bucket_total{bucket="3_10"} 1633
telemt_desync_frames_bucket_total{bucket="gt_10"} 1302
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 16068
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15143
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 916
telemt_user_connections_total{user="hello"} 1093092
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 17193736487 (16.01 GB)
telemt_user_octets_to_client{user="hello"} 501090280625 (466.68 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 104457.2 (29h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 820230
telemt_connections_bad_total 96431
telemt_handshake_timeouts_total 6643
telemt_upstream_connect_attempt_total 43418
telemt_upstream_connect_success_total 42824
telemt_upstream_connect_fail_total 593
telemt_upstream_connect_attempts_per_request{bucket="1"} 43417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15239
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 407
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 593
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 56088
telemt_me_reconnect_success_total 21133
telemt_me_reader_eof_total 22999
telemt_me_idle_close_by_peer_total 22997
telemt_me_route_drop_no_conn_total 260545
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 659338
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3126
telemt_desync_full_logged_total 921
telemt_desync_suppressed_total 2205
telemt_desync_frames_bucket_total{bucket="1_2"} 994
telemt_desync_frames_bucket_total{bucket="3_10"} 1247
telemt_desync_frames_bucket_total{bucket="gt_10"} 885
telemt_pool_swap_total 52
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22578
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 21125
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1445
telemt_user_connections_total{user="hello"} 675947
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 13402586800 (12.48 GB)
telemt_user_octets_to_client{user="hello"} 336245911928 (313.15 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 104618.6 (29h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1055001
telemt_connections_bad_total 95508
telemt_handshake_timeouts_total 9550
telemt_upstream_connect_attempt_total 20741
telemt_upstream_connect_success_total 20626
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 20741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26673
telemt_me_reconnect_success_total 15392
telemt_me_reader_eof_total 16713
telemt_me_idle_close_by_peer_total 16711
telemt_me_route_drop_no_conn_total 705807
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1021219
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 91
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15995
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15378
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 603
telemt_user_connections_total{user="hello"} 882927
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 14263666708 (13.28 GB)
telemt_user_octets_to_client{user="hello"} 373541466488 (347.89 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 52385.3 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378743
telemt_connections_bad_total 44642
telemt_handshake_timeouts_total 10752
telemt_upstream_connect_attempt_total 19855
telemt_upstream_connect_success_total 19672
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 19855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 28474
telemt_me_reconnect_success_total 16876
telemt_me_reader_eof_total 17851
telemt_me_idle_close_by_peer_total 17851
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 95351
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283528
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1035
telemt_desync_full_logged_total 327
telemt_desync_suppressed_total 708
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 437
telemt_desync_frames_bucket_total{bucket="gt_10"} 384
telemt_pool_swap_total 32
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17435
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 16847
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 559
telemt_user_connections_total{user="hello"} 283469
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 22017477497 (20.51 GB)
telemt_user_octets_to_client{user="hello"} 232564598898 (216.59 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 19
```