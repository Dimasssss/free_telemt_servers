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

# Server Metrics 2026-03-17 21:37:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 96748.4 (26h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1187020
telemt_connections_bad_total 8636
telemt_handshake_timeouts_total 31556
telemt_upstream_connect_attempt_total 21972
telemt_upstream_connect_success_total 21481
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 21972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31474
telemt_me_reconnect_success_total 14344
telemt_me_reader_eof_total 15591
telemt_me_idle_close_by_peer_total 15590
telemt_me_route_drop_no_conn_total 529852
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1088343
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7198
telemt_desync_full_logged_total 2076
telemt_desync_suppressed_total 5122
telemt_desync_frames_bucket_total{bucket="1_2"} 1929
telemt_desync_frames_bucket_total{bucket="3_10"} 2726
telemt_desync_frames_bucket_total{bucket="gt_10"} 2543
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 15091
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14322
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 747
telemt_user_connections_total{user="hello"} 1082576
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 19406945043 (18.07 GB)
telemt_user_octets_to_client{user="hello"} 384307741807 (357.91 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 96999.9 (26h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1241605
telemt_connections_bad_total 59610
telemt_handshake_timeouts_total 44194
telemt_upstream_connect_attempt_total 457439
telemt_upstream_connect_success_total 456548
telemt_upstream_connect_fail_total 891
telemt_upstream_connect_attempts_per_request{bucket="1"} 457439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30502
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 891
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57860
telemt_me_reconnect_success_total 14707
telemt_me_reader_eof_total 16681
telemt_me_idle_close_by_peer_total 16681
telemt_me_route_drop_no_conn_total 316972
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636683
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2805
telemt_desync_full_logged_total 900
telemt_desync_suppressed_total 1905
telemt_desync_frames_bucket_total{bucket="1_2"} 529
telemt_desync_frames_bucket_total{bucket="3_10"} 1164
telemt_desync_frames_bucket_total{bucket="gt_10"} 1112
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 16238
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14691
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1531
telemt_user_connections_total{user="hello"} 1073113
telemt_user_connections_current{user="hello"} 1139
telemt_user_octets_from_client{user="hello"} 14832931526 (13.81 GB)
telemt_user_octets_to_client{user="hello"} 358946509782 (334.29 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 96776.0 (26h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 702520
telemt_connections_bad_total 41225
telemt_handshake_timeouts_total 22658
telemt_upstream_connect_attempt_total 23070
telemt_upstream_connect_success_total 22935
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 23070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12343
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38722
telemt_me_reconnect_success_total 18046
telemt_me_reader_eof_total 19691
telemt_me_idle_close_by_peer_total 19684
telemt_me_route_drop_no_conn_total 295515
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 605163
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1951
telemt_desync_full_logged_total 593
telemt_desync_suppressed_total 1358
telemt_desync_frames_bucket_total{bucket="1_2"} 544
telemt_desync_frames_bucket_total{bucket="3_10"} 766
telemt_desync_frames_bucket_total{bucket="gt_10"} 641
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18939
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18034
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 893
telemt_user_connections_total{user="hello"} 603435
telemt_user_connections_current{user="hello"} 818
telemt_user_octets_from_client{user="hello"} 30448405992 (28.36 GB)
telemt_user_octets_to_client{user="hello"} 262555538636 (244.52 GB)
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 96835.4 (26h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1202984
telemt_connections_bad_total 38323
telemt_handshake_timeouts_total 21349
telemt_upstream_connect_attempt_total 82706
telemt_upstream_connect_success_total 82280
telemt_upstream_connect_fail_total 426
telemt_upstream_connect_attempts_per_request{bucket="1"} 82706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12067
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 426
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34383
telemt_me_reconnect_success_total 14063
telemt_me_reader_eof_total 15520
telemt_me_idle_close_by_peer_total 15518
telemt_me_route_drop_no_conn_total 498967
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 983562
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3432
telemt_desync_full_logged_total 1107
telemt_desync_suppressed_total 2325
telemt_desync_frames_bucket_total{bucket="1_2"} 850
telemt_desync_frames_bucket_total{bucket="3_10"} 1442
telemt_desync_frames_bucket_total{bucket="gt_10"} 1140
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 14962
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14054
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 899
telemt_user_connections_total{user="hello"} 1046060
telemt_user_connections_current{user="hello"} 923
telemt_user_octets_from_client{user="hello"} 16329495983 (15.21 GB)
telemt_user_octets_to_client{user="hello"} 447181577453 (416.47 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 96807.3 (26h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 758664
telemt_connections_bad_total 91375
telemt_handshake_timeouts_total 6358
telemt_upstream_connect_attempt_total 41613
telemt_upstream_connect_success_total 41056
telemt_upstream_connect_fail_total 557
telemt_upstream_connect_attempts_per_request{bucket="1"} 41613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 397
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 557
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 52211
telemt_me_reconnect_success_total 19725
telemt_me_reader_eof_total 21454
telemt_me_idle_close_by_peer_total 21452
telemt_me_route_drop_no_conn_total 238216
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 604467
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2763
telemt_desync_full_logged_total 812
telemt_desync_suppressed_total 1951
telemt_desync_frames_bucket_total{bucket="1_2"} 889
telemt_desync_frames_bucket_total{bucket="3_10"} 1116
telemt_desync_frames_bucket_total{bucket="gt_10"} 758
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21072
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 19717
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1347
telemt_user_connections_total{user="hello"} 621081
telemt_user_connections_current{user="hello"} 830
telemt_user_octets_from_client{user="hello"} 12032262960 (11.21 GB)
telemt_user_octets_to_client{user="hello"} 304972053556 (284.03 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 96968.1 (26h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 996739
telemt_connections_bad_total 74960
telemt_handshake_timeouts_total 9383
telemt_upstream_connect_attempt_total 19146
telemt_upstream_connect_success_total 19034
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 19146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25470
telemt_me_reconnect_success_total 14193
telemt_me_reader_eof_total 15417
telemt_me_idle_close_by_peer_total 15415
telemt_me_route_drop_no_conn_total 685288
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 987481
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2046
telemt_desync_full_logged_total 712
telemt_desync_suppressed_total 1334
telemt_desync_frames_bucket_total{bucket="1_2"} 459
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 811
telemt_pool_swap_total 82
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 14780
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14179
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 587
telemt_user_connections_total{user="hello"} 850513
telemt_user_connections_current{user="hello"} 479
telemt_user_octets_from_client{user="hello"} 13292549132 (12.38 GB)
telemt_user_octets_to_client{user="hello"} 363565447776 (338.60 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 44735.4 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334746
telemt_connections_bad_total 42909
telemt_handshake_timeouts_total 10522
telemt_upstream_connect_attempt_total 17851
telemt_upstream_connect_success_total 17687
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 17851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26876
telemt_me_reconnect_success_total 15283
telemt_me_reader_eof_total 16149
telemt_me_idle_close_by_peer_total 16149
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 82236
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255357
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 823
telemt_desync_full_logged_total 241
telemt_desync_suppressed_total 582
telemt_desync_frames_bucket_total{bucket="1_2"} 204
telemt_desync_frames_bucket_total{bucket="3_10"} 317
telemt_desync_frames_bucket_total{bucket="gt_10"} 302
telemt_pool_swap_total 23
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15823
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15255
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 255299
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 21044762273 (19.60 GB)
telemt_user_octets_to_client{user="hello"} 213539754326 (198.87 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 54
```