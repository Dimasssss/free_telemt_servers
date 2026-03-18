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

# Server Metrics 2026-03-18 00:05:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 105619.8 (29h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1250288
telemt_connections_bad_total 9413
telemt_handshake_timeouts_total 32387
telemt_upstream_connect_attempt_total 23708
telemt_upstream_connect_success_total 23211
telemt_upstream_connect_fail_total 497
telemt_upstream_connect_attempts_per_request{bucket="1"} 23708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11034
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 497
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32774
telemt_me_reconnect_success_total 15639
telemt_me_reader_eof_total 16987
telemt_me_idle_close_by_peer_total 16986
telemt_me_route_drop_no_conn_total 552460
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1148584
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7496
telemt_desync_full_logged_total 2191
telemt_desync_suppressed_total 5305
telemt_desync_frames_bucket_total{bucket="1_2"} 2006
telemt_desync_frames_bucket_total{bucket="3_10"} 2841
telemt_desync_frames_bucket_total{bucket="gt_10"} 2649
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 16404
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15617
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 765
telemt_user_connections_total{user="hello"} 1142806
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 22653886999 (21.10 GB)
telemt_user_octets_to_client{user="hello"} 410997101819 (382.77 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 105871.0 (29h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1326155
telemt_connections_bad_total 61457
telemt_handshake_timeouts_total 45710
telemt_upstream_connect_attempt_total 462624
telemt_upstream_connect_success_total 461082
telemt_upstream_connect_fail_total 1542
telemt_upstream_connect_attempts_per_request{bucket="1"} 462624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 385629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32107
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1542
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 121780
telemt_me_reconnect_success_total 16353
telemt_me_reader_eof_total 18430
telemt_me_idle_close_by_peer_total 18420
telemt_me_route_drop_no_conn_total 344242
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 712347
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3256
telemt_desync_full_logged_total 1075
telemt_desync_suppressed_total 2181
telemt_desync_frames_bucket_total{bucket="1_2"} 631
telemt_desync_frames_bucket_total{bucket="3_10"} 1338
telemt_desync_frames_bucket_total{bucket="gt_10"} 1287
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 17897
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 16335
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1544
telemt_user_connections_total{user="hello"} 1151223
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 15717715768 (14.64 GB)
telemt_user_octets_to_client{user="hello"} 395210154620 (368.07 GB)
telemt_user_msgs_from_client{user="hello"} 7437291
telemt_user_msgs_to_client{user="hello"} 31790605
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 105647.2 (29h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 783555
telemt_connections_bad_total 50273
telemt_handshake_timeouts_total 23814
telemt_upstream_connect_attempt_total 24842
telemt_upstream_connect_success_total 24698
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 24842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13272
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40053
telemt_me_reconnect_success_total 19372
telemt_me_reader_eof_total 21111
telemt_me_idle_close_by_peer_total 21104
telemt_me_route_drop_no_conn_total 318122
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 666068
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2136
telemt_desync_full_logged_total 696
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 607
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 703
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 20283
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19360
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 911
telemt_user_connections_total{user="hello"} 664286
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 32033029756 (29.83 GB)
telemt_user_octets_to_client{user="hello"} 293777339496 (273.60 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 105706.6 (29h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1271324
telemt_connections_bad_total 50859
telemt_handshake_timeouts_total 21707
telemt_upstream_connect_attempt_total 86043
telemt_upstream_connect_success_total 84629
telemt_upstream_connect_fail_total 1414
telemt_upstream_connect_attempts_per_request{bucket="1"} 86043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12993
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1414
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35691
telemt_me_reconnect_success_total 15332
telemt_me_reader_eof_total 16930
telemt_me_idle_close_by_peer_total 16928
telemt_me_route_drop_no_conn_total 521430
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1035573
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3901
telemt_desync_full_logged_total 1289
telemt_desync_suppressed_total 2612
telemt_desync_frames_bucket_total{bucket="1_2"} 950
telemt_desync_frames_bucket_total{bucket="3_10"} 1641
telemt_desync_frames_bucket_total{bucket="gt_10"} 1310
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 16259
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15322
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 927
telemt_user_connections_total{user="hello"} 1098698
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 17253831271 (16.07 GB)
telemt_user_octets_to_client{user="hello"} 506625140470 (471.83 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 105678.5 (29h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 827733
telemt_connections_bad_total 97623
telemt_handshake_timeouts_total 6668
telemt_upstream_connect_attempt_total 43850
telemt_upstream_connect_success_total 43249
telemt_upstream_connect_fail_total 601
telemt_upstream_connect_attempts_per_request{bucket="1"} 43850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 410
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 601
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 56438
telemt_me_reconnect_success_total 21482
telemt_me_reader_eof_total 23367
telemt_me_idle_close_by_peer_total 23365
telemt_me_route_drop_no_conn_total 262443
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 665403
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3150
telemt_desync_full_logged_total 932
telemt_desync_suppressed_total 2218
telemt_desync_frames_bucket_total{bucket="1_2"} 998
telemt_desync_frames_bucket_total{bucket="3_10"} 1258
telemt_desync_frames_bucket_total{bucket="gt_10"} 894
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22927
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 21474
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1445
telemt_user_connections_total{user="hello"} 682011
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 13458567196 (12.53 GB)
telemt_user_octets_to_client{user="hello"} 341320422928 (317.88 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 105839.8 (29h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1064081
telemt_connections_bad_total 98747
telemt_handshake_timeouts_total 9576
telemt_upstream_connect_attempt_total 21010
telemt_upstream_connect_success_total 20894
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 21010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10803
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26898
telemt_me_reconnect_success_total 15616
telemt_me_reader_eof_total 16953
telemt_me_idle_close_by_peer_total 16951
telemt_me_route_drop_no_conn_total 714288
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1029973
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
telemt_pool_swap_total 92
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16221
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15602
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 605
telemt_user_connections_total{user="hello"} 887846
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 14302165860 (13.32 GB)
telemt_user_octets_to_client{user="hello"} 375771290636 (349.96 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 53606.7 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385064
telemt_connections_bad_total 44666
telemt_handshake_timeouts_total 10786
telemt_upstream_connect_attempt_total 20256
telemt_upstream_connect_success_total 20072
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 20256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 28831
telemt_me_reconnect_success_total 17232
telemt_me_reader_eof_total 18226
telemt_me_idle_close_by_peer_total 18226
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 96229
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 286121
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1066
telemt_desync_full_logged_total 336
telemt_desync_suppressed_total 730
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 451
telemt_desync_frames_bucket_total{bucket="gt_10"} 401
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17793
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 17202
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 286062
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 22069550241 (20.55 GB)
telemt_user_octets_to_client{user="hello"} 235061852718 (218.92 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 33
```