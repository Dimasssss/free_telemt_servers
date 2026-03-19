# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-19 20:48:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 12649.4 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340799
telemt_connections_bad_total 16368
telemt_connections_current 970
telemt_connections_me_current 970
telemt_handshake_timeouts_total 5169
telemt_upstream_connect_attempt_total 1968
telemt_upstream_connect_success_total 1950
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 1968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1308
telemt_me_reconnect_success_total 1299
telemt_me_reader_eof_total 1367
telemt_me_idle_close_by_peer_total 1367
telemt_me_route_drop_no_conn_total 104092
telemt_me_route_drop_channel_closed_total 47
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268536
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1356
telemt_desync_full_logged_total 459
telemt_desync_suppressed_total 897
telemt_desync_frames_bucket_total{bucket="1_2"} 285
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 676
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 1332
telemt_me_writer_restored_same_endpoint_total 1286
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 268788
telemt_user_connections_current{user="hello"} 970
telemt_user_octets_from_client{user="hello"} 10642964332 (9.91 GB)
telemt_user_octets_to_client{user="hello"} 97684584260 (90.98 GB)
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 29104.7 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2576525
telemt_connections_bad_total 109428
telemt_connections_current 2674
telemt_connections_me_current 2674
telemt_handshake_timeouts_total 49743
telemt_upstream_connect_attempt_total 6043
telemt_upstream_connect_success_total 5949
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 6043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7463
telemt_me_reconnect_success_total 3235
telemt_me_reader_eof_total 3488
telemt_me_idle_close_by_peer_total 3488
telemt_me_route_drop_no_conn_total 1372807
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2191666
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9556
telemt_desync_full_logged_total 3125
telemt_desync_suppressed_total 6431
telemt_desync_frames_bucket_total{bucket="1_2"} 1761
telemt_desync_frames_bucket_total{bucket="3_10"} 3749
telemt_desync_frames_bucket_total{bucket="gt_10"} 4046
telemt_pool_swap_total 22
telemt_me_writer_close_signal_drop_total 38
telemt_me_writer_removed_unexpected_total 3398
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3180
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 2191619
telemt_user_connections_current{user="hello"} 2674
telemt_user_octets_from_client{user="hello"} 33713940042 (31.40 GB)
telemt_user_octets_to_client{user="hello"} 774230790874 (721.06 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 978
telemt_user_unique_ips_recent_window{user="hello"} 308
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 29082.7 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2462902
telemt_connections_bad_total 388439
telemt_connections_current 2039
telemt_connections_me_current 2039
telemt_handshake_timeouts_total 28734
telemt_upstream_connect_attempt_total 4530
telemt_upstream_connect_success_total 4497
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 4530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3931
telemt_me_reconnect_success_total 3009
telemt_me_reader_eof_total 3116
telemt_me_idle_close_by_peer_total 3115
telemt_me_route_drop_no_conn_total 1817260
telemt_me_route_drop_channel_closed_total 163
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1771924
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6647
telemt_desync_full_logged_total 1989
telemt_desync_suppressed_total 4658
telemt_desync_frames_bucket_total{bucket="1_2"} 1705
telemt_desync_frames_bucket_total{bucket="3_10"} 2499
telemt_desync_frames_bucket_total{bucket="gt_10"} 2443
telemt_pool_swap_total 26
telemt_me_writer_close_signal_drop_total 57
telemt_me_writer_removed_unexpected_total 3020
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3008
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 1767867
telemt_user_connections_current{user="hello"} 2039
telemt_user_octets_from_client{user="hello"} 25191135500 (23.46 GB)
telemt_user_octets_to_client{user="hello"} 620768849684 (578.14 GB)
telemt_user_unique_ips_current{user="hello"} 746
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 29070.6 (8h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2208000
telemt_connections_bad_total 88712
telemt_connections_current 1857
telemt_connections_me_current 1857
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 27507
telemt_upstream_connect_attempt_total 31810
telemt_upstream_connect_success_total 30257
telemt_upstream_connect_fail_total 1553
telemt_upstream_connect_attempts_per_request{bucket="1"} 31810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4934
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1553
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6013
telemt_me_reconnect_success_total 3471
telemt_me_reader_eof_total 3610
telemt_me_idle_close_by_peer_total 3609
telemt_me_route_drop_no_conn_total 1777296
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1884880
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7546
telemt_desync_full_logged_total 2344
telemt_desync_suppressed_total 5202
telemt_desync_frames_bucket_total{bucket="1_2"} 1882
telemt_desync_frames_bucket_total{bucket="3_10"} 2728
telemt_desync_frames_bucket_total{bucket="gt_10"} 2936
telemt_pool_swap_total 16
telemt_me_writer_close_signal_drop_total 291
telemt_me_writer_removed_unexpected_total 3937
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3467
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 1909069
telemt_user_connections_current{user="hello"} 1857
telemt_user_octets_from_client{user="hello"} 31574563400 (29.41 GB)
telemt_user_octets_to_client{user="hello"} 463126798010 (431.32 GB)
telemt_user_msgs_from_client{user="hello"} 63004
telemt_user_msgs_to_client{user="hello"} 130023
telemt_user_unique_ips_current{user="hello"} 680
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 82793.7 (22h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5879443
telemt_connections_bad_total 1029297
telemt_connections_current 2605
telemt_connections_me_current 2605
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 107278
telemt_upstream_connect_attempt_total 66071
telemt_upstream_connect_success_total 63570
telemt_upstream_connect_fail_total 2501
telemt_upstream_connect_attempts_per_request{bucket="1"} 66071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2501
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75686
telemt_me_reconnect_success_total 10270
telemt_me_reader_eof_total 10839
telemt_me_idle_close_by_peer_total 10836
telemt_me_route_drop_no_conn_total 2691120
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4147938
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18206
telemt_desync_full_logged_total 5653
telemt_desync_suppressed_total 12553
telemt_desync_frames_bucket_total{bucket="1_2"} 3119
telemt_desync_frames_bucket_total{bucket="3_10"} 7535
telemt_desync_frames_bucket_total{bucket="gt_10"} 7552
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 10528
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10246
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 4195998
telemt_user_connections_current{user="hello"} 2605
telemt_user_octets_from_client{user="hello"} 65423155391 (60.93 GB)
telemt_user_octets_to_client{user="hello"} 1600094516280 (1.46 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 881
telemt_user_unique_ips_recent_window{user="hello"} 302
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 29033.8 (8h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 593828
telemt_connections_bad_total 46200
telemt_connections_current 522
telemt_connections_me_current 522
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11468
telemt_upstream_connect_attempt_total 8444
telemt_upstream_connect_success_total 8247
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 8444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 552
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 3829
telemt_me_reconnect_success_total 3767
telemt_me_reader_eof_total 3910
telemt_me_idle_close_by_peer_total 3909
telemt_me_route_drop_no_conn_total 391839
telemt_me_route_drop_channel_closed_total 140
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 472718
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1235
telemt_desync_full_logged_total 414
telemt_desync_suppressed_total 821
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 502
telemt_desync_frames_bucket_total{bucket="gt_10"} 538
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 138
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 3800
telemt_me_writer_restored_same_endpoint_total 3758
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 491357
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 5526975504 (5.15 GB)
telemt_user_octets_to_client{user="hello"} 106452914046 (99.14 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 29035.1 (8h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1739105
telemt_connections_bad_total 102922
telemt_connections_current 1954
telemt_connections_me_current 1954
telemt_handshake_timeouts_total 29921
telemt_upstream_connect_attempt_total 4848
telemt_upstream_connect_success_total 4811
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 4848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3345
telemt_me_reconnect_success_total 3313
telemt_me_reader_eof_total 3482
telemt_me_idle_close_by_peer_total 3482
telemt_me_route_drop_no_conn_total 655795
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1511050
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7988
telemt_desync_full_logged_total 2480
telemt_desync_suppressed_total 5508
telemt_desync_frames_bucket_total{bucket="1_2"} 1498
telemt_desync_frames_bucket_total{bucket="3_10"} 2780
telemt_desync_frames_bucket_total{bucket="gt_10"} 3710
telemt_pool_swap_total 27
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3373
telemt_me_writer_restored_same_endpoint_total 3296
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1510210
telemt_user_connections_current{user="hello"} 1954
telemt_user_octets_from_client{user="hello"} 25665245872 (23.90 GB)
telemt_user_octets_to_client{user="hello"} 731766343116 (681.51 GB)
telemt_user_unique_ips_current{user="hello"} 720
telemt_user_unique_ips_recent_window{user="hello"} 220
```