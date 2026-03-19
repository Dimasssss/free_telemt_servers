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

# Server Metrics 2026-03-19 08:36:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 38888.7 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 742278
telemt_connections_bad_total 75222
telemt_connections_current 1539
telemt_connections_me_current 1539
telemt_handshake_timeouts_total 27770
telemt_upstream_connect_attempt_total 7391
telemt_upstream_connect_success_total 7261
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 7391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 6451
telemt_me_reconnect_success_total 5297
telemt_me_reader_eof_total 5624
telemt_me_idle_close_by_peer_total 5623
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 211889
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 567938
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3635
telemt_desync_full_logged_total 1067
telemt_desync_suppressed_total 2568
telemt_desync_frames_bucket_total{bucket="1_2"} 1248
telemt_desync_frames_bucket_total{bucket="3_10"} 1349
telemt_desync_frames_bucket_total{bucket="gt_10"} 1038
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5393
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5279
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 564952
telemt_user_connections_current{user="hello"} 1539
telemt_user_octets_from_client{user="hello"} 8540855380 (7.95 GB)
telemt_user_octets_to_client{user="hello"} 187837560744 (174.94 GB)
telemt_user_unique_ips_current{user="hello"} 549
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 38893.8 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1815449
telemt_connections_bad_total 104437
telemt_connections_current 4221
telemt_connections_me_current 4221
telemt_handshake_timeouts_total 41427
telemt_upstream_connect_attempt_total 7337
telemt_upstream_connect_success_total 7201
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 7337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 6377
telemt_me_reconnect_success_total 5218
telemt_me_reader_eof_total 5533
telemt_me_idle_close_by_peer_total 5533
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 792589
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1501736
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6659
telemt_desync_full_logged_total 2248
telemt_desync_suppressed_total 4411
telemt_desync_frames_bucket_total{bucket="1_2"} 1198
telemt_desync_frames_bucket_total{bucket="3_10"} 2523
telemt_desync_frames_bucket_total{bucket="gt_10"} 2938
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5350
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5196
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 1501528
telemt_user_connections_current{user="hello"} 4221
telemt_user_octets_from_client{user="hello"} 25816836044 (24.04 GB)
telemt_user_octets_to_client{user="hello"} 571500547256 (532.25 GB)
telemt_user_unique_ips_current{user="hello"} 1382
telemt_user_unique_ips_recent_window{user="hello"} 654
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 38891.1 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1534687
telemt_connections_bad_total 196714
telemt_connections_current 2991
telemt_connections_me_current 2991
telemt_handshake_timeouts_total 38217
telemt_upstream_connect_attempt_total 6940
telemt_upstream_connect_success_total 6940
telemt_upstream_connect_attempts_per_request{bucket="1"} 6940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3311
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 4989
telemt_me_reconnect_success_total 4959
telemt_me_reader_eof_total 5255
telemt_me_idle_close_by_peer_total 5255
telemt_me_route_drop_no_conn_total 690433
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1178296
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5542
telemt_desync_full_logged_total 1724
telemt_desync_suppressed_total 3818
telemt_desync_frames_bucket_total{bucket="1_2"} 1214
telemt_desync_frames_bucket_total{bucket="3_10"} 1989
telemt_desync_frames_bucket_total{bucket="gt_10"} 2339
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5051
telemt_me_writer_restored_same_endpoint_total 4943
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 1177859
telemt_user_connections_current{user="hello"} 2991
telemt_user_octets_from_client{user="hello"} 19465465980 (18.13 GB)
telemt_user_octets_to_client{user="hello"} 577318472232 (537.67 GB)
telemt_user_unique_ips_current{user="hello"} 1058
telemt_user_unique_ips_recent_window{user="hello"} 452
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 38945.1 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1603759
telemt_connections_bad_total 96169
telemt_connections_current 3011
telemt_connections_me_current 3011
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 40934
telemt_upstream_connect_attempt_total 15172
telemt_upstream_connect_success_total 15073
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 15171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7331
telemt_me_reconnect_success_total 4940
telemt_me_reader_eof_total 5249
telemt_me_idle_close_by_peer_total 5248
telemt_me_route_drop_no_conn_total 711924
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1148819
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4207
telemt_desync_full_logged_total 1432
telemt_desync_suppressed_total 2775
telemt_desync_frames_bucket_total{bucket="1_2"} 832
telemt_desync_frames_bucket_total{bucket="3_10"} 1652
telemt_desync_frames_bucket_total{bucket="gt_10"} 1723
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5196
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 4916
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 1155638
telemt_user_connections_current{user="hello"} 3011
telemt_user_octets_from_client{user="hello"} 14870604388 (13.85 GB)
telemt_user_octets_to_client{user="hello"} 361426290222 (336.60 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 983
telemt_user_unique_ips_recent_window{user="hello"} 465
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 38887.3 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1887751
telemt_connections_bad_total 486113
telemt_connections_current 3654
telemt_connections_me_current 3654
telemt_handshake_timeouts_total 39367
telemt_upstream_connect_attempt_total 6691
telemt_upstream_connect_success_total 6643
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 6690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 4708
telemt_me_reconnect_success_total 4670
telemt_me_reader_eof_total 4959
telemt_me_idle_close_by_peer_total 4959
telemt_me_route_drop_no_conn_total 504595
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1169636
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5750
telemt_desync_full_logged_total 1785
telemt_desync_suppressed_total 3965
telemt_desync_frames_bucket_total{bucket="1_2"} 1173
telemt_desync_frames_bucket_total{bucket="3_10"} 2580
telemt_desync_frames_bucket_total{bucket="gt_10"} 1997
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 4736
telemt_me_writer_restored_same_endpoint_total 4646
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 1169215
telemt_user_connections_current{user="hello"} 3654
telemt_user_octets_from_client{user="hello"} 23331671396 (21.73 GB)
telemt_user_octets_to_client{user="hello"} 547223045556 (509.64 GB)
telemt_user_unique_ips_current{user="hello"} 1221
telemt_user_unique_ips_recent_window{user="hello"} 583
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 38899.2 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324645
telemt_connections_bad_total 14742
telemt_connections_current 823
telemt_connections_me_current 823
telemt_handshake_timeouts_total 2827
telemt_upstream_connect_attempt_total 9959
telemt_upstream_connect_success_total 9697
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 9959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 13102
telemt_me_reconnect_success_total 7722
telemt_me_reader_eof_total 8196
telemt_me_idle_close_by_peer_total 8196
telemt_me_route_drop_no_conn_total 149091
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290647
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 409
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 266
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7944
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7692
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 290611
telemt_user_connections_current{user="hello"} 823
telemt_user_octets_from_client{user="hello"} 4237272320 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 127835457404 (119.06 GB)
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 38889.8 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1243418
telemt_connections_bad_total 103915
telemt_connections_current 3097
telemt_connections_me_current 3097
telemt_handshake_timeouts_total 54482
telemt_upstream_connect_attempt_total 7850
telemt_upstream_connect_success_total 7849
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 7216
telemt_me_reconnect_success_total 5873
telemt_me_reader_eof_total 6235
telemt_me_idle_close_by_peer_total 6234
telemt_me_route_drop_no_conn_total 490008
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1036897
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6169
telemt_desync_full_logged_total 2026
telemt_desync_suppressed_total 4143
telemt_desync_frames_bucket_total{bucket="1_2"} 1174
telemt_desync_frames_bucket_total{bucket="3_10"} 2319
telemt_desync_frames_bucket_total{bucket="gt_10"} 2676
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5982
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5858
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 1035838
telemt_user_connections_current{user="hello"} 3097
telemt_user_octets_from_client{user="hello"} 14546835576 (13.55 GB)
telemt_user_octets_to_client{user="hello"} 524822797128 (488.78 GB)
telemt_user_unique_ips_current{user="hello"} 999
telemt_user_unique_ips_recent_window{user="hello"} 446
```