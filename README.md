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

# Server Metrics 2026-03-18 07:18:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 131584.7 (36h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1759554
telemt_connections_bad_total 11631
telemt_handshake_timeouts_total 37260
telemt_upstream_connect_attempt_total 28529
telemt_upstream_connect_success_total 28005
telemt_upstream_connect_fail_total 524
telemt_upstream_connect_attempts_per_request{bucket="1"} 28529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13476
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 524
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 286
telemt_me_reconnect_attempts_total 36311
telemt_me_reconnect_success_total 19150
telemt_me_reader_eof_total 20746
telemt_me_idle_close_by_peer_total 20745
telemt_me_route_drop_no_conn_total 653732
telemt_me_route_drop_channel_closed_total 189
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1435043
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8633
telemt_desync_full_logged_total 2612
telemt_desync_suppressed_total 6021
telemt_desync_frames_bucket_total{bucket="1_2"} 2224
telemt_desync_frames_bucket_total{bucket="3_10"} 3335
telemt_desync_frames_bucket_total{bucket="gt_10"} 3074
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 19972
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 19128
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 822
telemt_user_connections_total{user="hello"} 1429310
telemt_user_connections_current{user="hello"} 1152
telemt_user_octets_from_client{user="hello"} 33054190195 (30.78 GB)
telemt_user_octets_to_client{user="hello"} 509647241387 (474.65 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 131836.1 (36h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1850462
telemt_connections_bad_total 96653
telemt_handshake_timeouts_total 58581
telemt_upstream_connect_attempt_total 472084
telemt_upstream_connect_success_total 470434
telemt_upstream_connect_fail_total 1650
telemt_upstream_connect_attempts_per_request{bucket="1"} 472084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1650
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 411
telemt_me_reconnect_attempts_total 130214
telemt_me_reconnect_success_total 20951
telemt_me_reader_eof_total 23346
telemt_me_idle_close_by_peer_total 23333
telemt_me_route_drop_no_conn_total 516971
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1166193
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5317
telemt_desync_full_logged_total 1864
telemt_desync_suppressed_total 3453
telemt_desync_frames_bucket_total{bucket="1_2"} 1007
telemt_desync_frames_bucket_total{bucket="3_10"} 2156
telemt_desync_frames_bucket_total{bucket="gt_10"} 2154
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22670
telemt_me_refill_failed_total 3408
telemt_me_writer_restored_same_endpoint_total 20933
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1719
telemt_user_connections_total{user="hello"} 1608545
telemt_user_connections_current{user="hello"} 2510
telemt_user_octets_from_client{user="hello"} 25337421725 (23.60 GB)
telemt_user_octets_to_client{user="hello"} 632144132350 (588.73 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 778
telemt_user_unique_ips_recent_window{user="hello"} 338
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 131612.0 (36h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1355896
telemt_connections_bad_total 85386
telemt_handshake_timeouts_total 32573
telemt_upstream_connect_attempt_total 29774
telemt_upstream_connect_success_total 29607
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 29774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15840
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 162
telemt_me_reconnect_attempts_total 43709
telemt_me_reconnect_success_total 22990
telemt_me_reader_eof_total 24974
telemt_me_idle_close_by_peer_total 24966
telemt_me_route_drop_no_conn_total 506722
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1003980
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3550
telemt_desync_full_logged_total 1181
telemt_desync_suppressed_total 2369
telemt_desync_frames_bucket_total{bucket="1_2"} 965
telemt_desync_frames_bucket_total{bucket="3_10"} 1365
telemt_desync_frames_bucket_total{bucket="gt_10"} 1220
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 23960
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22978
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 970
telemt_user_connections_total{user="hello"} 1002003
telemt_user_connections_current{user="hello"} 1667
telemt_user_octets_from_client{user="hello"} 49155577192 (45.78 GB)
telemt_user_octets_to_client{user="hello"} 484318377124 (451.06 GB)
telemt_user_unique_ips_current{user="hello"} 511
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 131671.4 (36h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1740644
telemt_connections_bad_total 85232
telemt_handshake_timeouts_total 30926
telemt_upstream_connect_attempt_total 92893
telemt_upstream_connect_success_total 90437
telemt_upstream_connect_fail_total 2456
telemt_upstream_connect_attempts_per_request{bucket="1"} 92893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 387
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2456
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 350
telemt_me_reconnect_attempts_total 40621
telemt_me_reconnect_success_total 19104
telemt_me_reader_eof_total 20942
telemt_me_idle_close_by_peer_total 20939
telemt_me_route_drop_no_conn_total 713257
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1436898
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5589
telemt_desync_full_logged_total 1765
telemt_desync_suppressed_total 3824
telemt_desync_frames_bucket_total{bucket="1_2"} 1308
telemt_desync_frames_bucket_total{bucket="3_10"} 2280
telemt_desync_frames_bucket_total{bucket="gt_10"} 2001
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 20130
telemt_me_refill_failed_total 663
telemt_me_writer_restored_same_endpoint_total 19084
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1026
telemt_user_connections_total{user="hello"} 1500086
telemt_user_connections_current{user="hello"} 2392
telemt_user_octets_from_client{user="hello"} 24821555830 (23.12 GB)
telemt_user_octets_to_client{user="hello"} 705075723334 (656.65 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 681
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 131643.3 (36h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1262345
telemt_connections_bad_total 113042
telemt_handshake_timeouts_total 13519
telemt_upstream_connect_attempt_total 49820
telemt_upstream_connect_success_total 49129
telemt_upstream_connect_fail_total 691
telemt_upstream_connect_attempts_per_request{bucket="1"} 49820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18459
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 691
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 64871
telemt_me_reconnect_success_total 26089
telemt_me_reader_eof_total 28294
telemt_me_idle_close_by_peer_total 28291
telemt_me_route_drop_no_conn_total 418471
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1041546
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4525
telemt_desync_full_logged_total 1398
telemt_desync_suppressed_total 3127
telemt_desync_frames_bucket_total{bucket="1_2"} 1189
telemt_desync_frames_bucket_total{bucket="3_10"} 1753
telemt_desync_frames_bucket_total{bucket="gt_10"} 1583
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27705
telemt_me_refill_failed_total 1206
telemt_me_writer_restored_same_endpoint_total 26081
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1616
telemt_user_connections_total{user="hello"} 1057905
telemt_user_connections_current{user="hello"} 2248
telemt_user_octets_from_client{user="hello"} 21071420752 (19.62 GB)
telemt_user_octets_to_client{user="hello"} 530094361660 (493.69 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 672
telemt_user_unique_ips_recent_window{user="hello"} 300
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 131804.6 (36h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1288189
telemt_connections_bad_total 134078
telemt_handshake_timeouts_total 10953
telemt_upstream_connect_attempt_total 26291
telemt_upstream_connect_success_total 26134
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 26291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13422
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 30885
telemt_me_reconnect_success_total 19582
telemt_me_reader_eof_total 21191
telemt_me_idle_close_by_peer_total 21188
telemt_me_route_drop_no_conn_total 855113
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1256754
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2487
telemt_desync_full_logged_total 873
telemt_desync_suppressed_total 1614
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 959
telemt_desync_frames_bucket_total{bucket="gt_10"} 981
telemt_pool_swap_total 119
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20233
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19568
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 651
telemt_user_connections_total{user="hello"} 1065407
telemt_user_connections_current{user="hello"} 945
telemt_user_octets_from_client{user="hello"} 16576128900 (15.44 GB)
telemt_user_octets_to_client{user="hello"} 469047360824 (436.83 GB)
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 79571.4 (22h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 712966
telemt_connections_bad_total 62801
telemt_handshake_timeouts_total 15331
telemt_upstream_connect_attempt_total 26770
telemt_upstream_connect_success_total 26483
telemt_upstream_connect_fail_total 287
telemt_upstream_connect_attempts_per_request{bucket="1"} 26770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 287
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 33995
telemt_me_reconnect_success_total 22374
telemt_me_reader_eof_total 23637
telemt_me_idle_close_by_peer_total 23637
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 204372
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 538231
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2255
telemt_desync_full_logged_total 774
telemt_desync_suppressed_total 1481
telemt_desync_frames_bucket_total{bucket="1_2"} 375
telemt_desync_frames_bucket_total{bucket="3_10"} 966
telemt_desync_frames_bucket_total{bucket="gt_10"} 914
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22979
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 22327
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 605
telemt_user_connections_total{user="hello"} 537931
telemt_user_connections_current{user="hello"} 1496
telemt_user_octets_from_client{user="hello"} 28306328833 (26.36 GB)
telemt_user_octets_to_client{user="hello"} 393783488950 (366.74 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 174
```