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

# Server Metrics 2026-03-19 21:34:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 15404.9 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381156
telemt_connections_bad_total 18805
telemt_connections_current 820
telemt_connections_me_current 820
telemt_handshake_timeouts_total 5603
telemt_upstream_connect_attempt_total 2470
telemt_upstream_connect_success_total 2447
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 2470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 1649
telemt_me_reconnect_success_total 1637
telemt_me_reader_eof_total 1729
telemt_me_idle_close_by_peer_total 1729
telemt_me_route_drop_no_conn_total 115989
telemt_me_route_drop_channel_closed_total 48
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302625
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1647
telemt_desync_full_logged_total 565
telemt_desync_suppressed_total 1082
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 505
telemt_desync_frames_bucket_total{bucket="gt_10"} 797
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 1676
telemt_me_writer_restored_same_endpoint_total 1624
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 302895
telemt_user_connections_current{user="hello"} 820
telemt_user_octets_from_client{user="hello"} 11014820392 (10.26 GB)
telemt_user_octets_to_client{user="hello"} 114170517216 (106.33 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 31859.2 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2689741
telemt_connections_bad_total 114163
telemt_connections_current 2093
telemt_connections_me_current 2093
telemt_handshake_timeouts_total 52665
telemt_upstream_connect_attempt_total 6525
telemt_upstream_connect_success_total 6422
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 6525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7806
telemt_me_reconnect_success_total 3577
telemt_me_reader_eof_total 3843
telemt_me_idle_close_by_peer_total 3843
telemt_me_route_drop_no_conn_total 1415040
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2293947
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10172
telemt_desync_full_logged_total 3307
telemt_desync_suppressed_total 6865
telemt_desync_frames_bucket_total{bucket="1_2"} 1889
telemt_desync_frames_bucket_total{bucket="3_10"} 3980
telemt_desync_frames_bucket_total{bucket="gt_10"} 4303
telemt_pool_swap_total 24
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 3744
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3522
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 2293825
telemt_user_connections_current{user="hello"} 2093
telemt_user_octets_from_client{user="hello"} 36265285166 (33.77 GB)
telemt_user_octets_to_client{user="hello"} 814770861946 (758.81 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 842
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 31837.4 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2625859
telemt_connections_bad_total 456004
telemt_connections_current 1567
telemt_connections_me_current 1567
telemt_handshake_timeouts_total 32570
telemt_upstream_connect_attempt_total 4960
telemt_upstream_connect_success_total 4921
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 4960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4227
telemt_me_reconnect_success_total 3301
telemt_me_reader_eof_total 3428
telemt_me_idle_close_by_peer_total 3427
telemt_me_route_drop_no_conn_total 1843411
telemt_me_route_drop_channel_closed_total 164
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1837246
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6984
telemt_desync_full_logged_total 2106
telemt_desync_suppressed_total 4878
telemt_desync_frames_bucket_total{bucket="1_2"} 1766
telemt_desync_frames_bucket_total{bucket="3_10"} 2644
telemt_desync_frames_bucket_total{bucket="gt_10"} 2574
telemt_pool_swap_total 29
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 3321
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3300
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1833184
telemt_user_connections_current{user="hello"} 1567
telemt_user_octets_from_client{user="hello"} 27219473388 (25.35 GB)
telemt_user_octets_to_client{user="hello"} 664353583228 (618.73 GB)
telemt_user_unique_ips_current{user="hello"} 616
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 31825.3 (8h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2296586
telemt_connections_bad_total 94696
telemt_connections_current 1607
telemt_connections_me_current 1607
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 28833
telemt_upstream_connect_attempt_total 35164
telemt_upstream_connect_success_total 33454
telemt_upstream_connect_fail_total 1710
telemt_upstream_connect_attempts_per_request{bucket="1"} 35164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5328
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1710
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6357
telemt_me_reconnect_success_total 3756
telemt_me_reader_eof_total 3893
telemt_me_idle_close_by_peer_total 3892
telemt_me_route_drop_no_conn_total 1804252
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1956863
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7880
telemt_desync_full_logged_total 2457
telemt_desync_suppressed_total 5423
telemt_desync_frames_bucket_total{bucket="1_2"} 1942
telemt_desync_frames_bucket_total{bucket="3_10"} 2862
telemt_desync_frames_bucket_total{bucket="gt_10"} 3076
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 347
telemt_me_writer_removed_unexpected_total 4263
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3752
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 507
telemt_user_connections_total{user="hello"} 1983807
telemt_user_connections_current{user="hello"} 1607
telemt_user_octets_from_client{user="hello"} 32832358164 (30.58 GB)
telemt_user_octets_to_client{user="hello"} 496215926119 (462.14 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 588
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 85548.3 (23h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5968391
telemt_connections_bad_total 1030480
telemt_connections_current 1949
telemt_connections_me_current 1949
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 108234
telemt_upstream_connect_attempt_total 66507
telemt_upstream_connect_success_total 64004
telemt_upstream_connect_fail_total 2503
telemt_upstream_connect_attempts_per_request{bucket="1"} 66507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1057
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2503
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75976
telemt_me_reconnect_success_total 10558
telemt_me_reader_eof_total 11144
telemt_me_idle_close_by_peer_total 11141
telemt_me_route_drop_no_conn_total 2725613
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4230768
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
telemt_desync_total 18589
telemt_desync_full_logged_total 5775
telemt_desync_suppressed_total 12814
telemt_desync_frames_bucket_total{bucket="1_2"} 3212
telemt_desync_frames_bucket_total{bucket="3_10"} 7681
telemt_desync_frames_bucket_total{bucket="gt_10"} 7696
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 10821
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10534
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 4278817
telemt_user_connections_current{user="hello"} 1949
telemt_user_octets_from_client{user="hello"} 66514980803 (61.95 GB)
telemt_user_octets_to_client{user="hello"} 1651261754008 (1.50 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 732
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 31788.3 (8h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 614648
telemt_connections_bad_total 48887
telemt_connections_current 492
telemt_connections_me_current 492
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11784
telemt_upstream_connect_attempt_total 8989
telemt_upstream_connect_success_total 8788
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 8989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5041
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4245
telemt_me_reconnect_success_total 4178
telemt_me_reader_eof_total 4353
telemt_me_idle_close_by_peer_total 4352
telemt_me_route_drop_no_conn_total 406741
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 494742
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
telemt_desync_total 1348
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 844
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 553
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 25
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 143
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4215
telemt_me_writer_restored_same_endpoint_total 4169
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 507883
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 6724568844 (6.26 GB)
telemt_user_octets_to_client{user="hello"} 114146565298 (106.31 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 31789.7 (8h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1815526
telemt_connections_bad_total 105880
telemt_connections_current 1770
telemt_connections_me_current 1770
telemt_handshake_timeouts_total 32658
telemt_upstream_connect_attempt_total 5286
telemt_upstream_connect_success_total 5246
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 5286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3651
telemt_me_reconnect_success_total 3617
telemt_me_reader_eof_total 3807
telemt_me_idle_close_by_peer_total 3807
telemt_me_route_drop_no_conn_total 681704
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1576919
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8439
telemt_desync_full_logged_total 2650
telemt_desync_suppressed_total 5789
telemt_desync_frames_bucket_total{bucket="1_2"} 1559
telemt_desync_frames_bucket_total{bucket="3_10"} 2943
telemt_desync_frames_bucket_total{bucket="gt_10"} 3937
telemt_pool_swap_total 30
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3686
telemt_me_writer_restored_same_endpoint_total 3600
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1576072
telemt_user_connections_current{user="hello"} 1770
telemt_user_octets_from_client{user="hello"} 26861052192 (25.02 GB)
telemt_user_octets_to_client{user="hello"} 776453021756 (723.13 GB)
telemt_user_unique_ips_current{user="hello"} 635
telemt_user_unique_ips_recent_window{user="hello"} 167
```