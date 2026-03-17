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

# Server Metrics 2026-03-17 16:01:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 76552.3 (21h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 858737
telemt_connections_bad_total 6351
telemt_handshake_timeouts_total 25120
telemt_upstream_connect_attempt_total 18271
telemt_upstream_connect_success_total 17800
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 18271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 26369
telemt_me_reconnect_success_total 11657
telemt_me_reader_eof_total 12671
telemt_me_idle_close_by_peer_total 12670
telemt_me_route_drop_no_conn_total 372130
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 784583
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5393
telemt_desync_full_logged_total 1496
telemt_desync_suppressed_total 3897
telemt_desync_frames_bucket_total{bucket="1_2"} 1565
telemt_desync_frames_bucket_total{bucket="3_10"} 2102
telemt_desync_frames_bucket_total{bucket="gt_10"} 1726
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 12275
telemt_me_refill_failed_total 454
telemt_me_writer_restored_same_endpoint_total 11635
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 782154
telemt_user_connections_current{user="hello"} 981
telemt_user_octets_from_client{user="hello"} 12350342115 (11.50 GB)
telemt_user_octets_to_client{user="hello"} 257335164247 (239.66 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 76804.2 (21h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 576799
telemt_connections_bad_total 32321
telemt_handshake_timeouts_total 28499
telemt_upstream_connect_attempt_total 132380
telemt_upstream_connect_success_total 131815
telemt_upstream_connect_fail_total 564
telemt_upstream_connect_attempts_per_request{bucket="1"} 132379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9728
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 564
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 42897
telemt_me_reconnect_success_total 13510
telemt_me_reader_eof_total 14981
telemt_me_idle_close_by_peer_total 14981
telemt_me_route_drop_no_conn_total 196726
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375662
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1494
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 1025
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 651
telemt_desync_frames_bucket_total{bucket="gt_10"} 507
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14591
telemt_me_refill_failed_total 914
telemt_me_writer_restored_same_endpoint_total 13494
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1081
telemt_user_connections_total{user="hello"} 490002
telemt_user_connections_current{user="hello"} 806
telemt_user_octets_from_client{user="hello"} 5407679819 (5.04 GB)
telemt_user_octets_to_client{user="hello"} 137400086605 (127.96 GB)
telemt_user_msgs_from_client{user="hello"} 1676163
telemt_user_msgs_to_client{user="hello"} 6288525
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 76579.4 (21h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289021
telemt_connections_bad_total 7876
telemt_handshake_timeouts_total 18822
telemt_upstream_connect_attempt_total 19773
telemt_upstream_connect_success_total 19669
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 19773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 32293
telemt_me_reconnect_success_total 15783
telemt_me_reader_eof_total 17163
telemt_me_idle_close_by_peer_total 17160
telemt_me_route_drop_no_conn_total 136989
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247653
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 824
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 585
telemt_desync_frames_bucket_total{bucket="1_2"} 298
telemt_desync_frames_bucket_total{bucket="3_10"} 370
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16508
telemt_me_refill_failed_total 513
telemt_me_writer_restored_same_endpoint_total 15772
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 725
telemt_user_connections_total{user="hello"} 247503
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 19327040876 (18.00 GB)
telemt_user_octets_to_client{user="hello"} 59642527780 (55.55 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 76638.8 (21h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 687043
telemt_connections_bad_total 9590
telemt_handshake_timeouts_total 14542
telemt_upstream_connect_attempt_total 62671
telemt_upstream_connect_success_total 62338
telemt_upstream_connect_fail_total 333
telemt_upstream_connect_attempts_per_request{bucket="1"} 62671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9755
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 333
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 31215
telemt_me_reconnect_success_total 11982
telemt_me_reader_eof_total 13228
telemt_me_idle_close_by_peer_total 13227
telemt_me_route_drop_no_conn_total 258882
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547961
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1872
telemt_desync_full_logged_total 635
telemt_desync_suppressed_total 1237
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 841
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12791
telemt_me_refill_failed_total 596
telemt_me_writer_restored_same_endpoint_total 11973
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 809
telemt_user_connections_total{user="hello"} 594221
telemt_user_connections_current{user="hello"} 763
telemt_user_octets_from_client{user="hello"} 7052023346 (6.57 GB)
telemt_user_octets_to_client{user="hello"} 178157256677 (165.92 GB)
telemt_user_msgs_from_client{user="hello"} 519466
telemt_user_msgs_to_client{user="hello"} 3849500
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 76610.7 (21h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306522
telemt_connections_bad_total 57927
telemt_handshake_timeouts_total 3759
telemt_upstream_connect_attempt_total 21751
telemt_upstream_connect_success_total 21272
telemt_upstream_connect_fail_total 478
telemt_upstream_connect_attempts_per_request{bucket="1"} 21750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 296
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 478
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 45607
telemt_me_reconnect_success_total 17006
telemt_me_reader_eof_total 18489
telemt_me_idle_close_by_peer_total 18487
telemt_me_route_drop_no_conn_total 88204
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231980
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1146
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 18180
telemt_me_refill_failed_total 889
telemt_me_writer_restored_same_endpoint_total 16998
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1174
telemt_user_connections_total{user="hello"} 232527
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 2857412943 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 85606226527 (79.73 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 76773.2 (21h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 750479
telemt_connections_bad_total 59848
telemt_handshake_timeouts_total 7149
telemt_upstream_connect_attempt_total 15479
telemt_upstream_connect_success_total 15396
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 15479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7884
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 21821
telemt_me_reconnect_success_total 11520
telemt_me_reader_eof_total 12536
telemt_me_idle_close_by_peer_total 12535
telemt_me_route_drop_no_conn_total 554454
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 767374
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1138
telemt_desync_full_logged_total 412
telemt_desync_suppressed_total 726
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 453
telemt_desync_frames_bucket_total{bucket="gt_10"} 414
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12028
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11506
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 508
telemt_user_connections_total{user="hello"} 645981
telemt_user_connections_current{user="hello"} 894
telemt_user_octets_from_client{user="hello"} 9414720592 (8.77 GB)
telemt_user_octets_to_client{user="hello"} 289618488376 (269.73 GB)
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 24538.8 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18988
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 314
telemt_upstream_connect_attempt_total 13224
telemt_upstream_connect_success_total 13113
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 13224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23251
telemt_me_reconnect_success_total 11681
telemt_me_reader_eof_total 12376
telemt_me_idle_close_by_peer_total 12376
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 9600
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18147
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 12172
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 11663
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 491
telemt_user_connections_total{user="hello"} 18202
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 566816549 (540.56 MB)
telemt_user_octets_to_client{user="hello"} 24721451538 (23.02 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 7
```