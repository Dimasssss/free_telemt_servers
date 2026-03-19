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

# Server Metrics 2026-03-19 17:56:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 2362.2 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75686
telemt_connections_bad_total 2174
telemt_connections_current 1511
telemt_connections_me_current 1511
telemt_handshake_timeouts_total 753
telemt_upstream_connect_attempt_total 362
telemt_upstream_connect_success_total 356
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 203
telemt_me_reconnect_success_total 202
telemt_me_reader_eof_total 192
telemt_me_idle_close_by_peer_total 192
telemt_me_route_drop_no_conn_total 25821
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66216
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 313
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 211
telemt_me_writer_restored_same_endpoint_total 189
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 66325
telemt_user_connections_current{user="hello"} 1511
telemt_user_octets_from_client{user="hello"} 1081163536 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 23260209820 (21.66 GB)
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 18817.7 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1893167
telemt_connections_bad_total 94106
telemt_connections_current 3766
telemt_connections_me_current 3766
telemt_handshake_timeouts_total 35528
telemt_upstream_connect_attempt_total 4409
telemt_upstream_connect_success_total 4355
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 4409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6386
telemt_me_reconnect_success_total 2162
telemt_me_reader_eof_total 2336
telemt_me_idle_close_by_peer_total 2336
telemt_me_route_drop_no_conn_total 1103928
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1567816
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6202
telemt_desync_full_logged_total 1942
telemt_desync_suppressed_total 4260
telemt_desync_frames_bucket_total{bucket="1_2"} 1202
telemt_desync_frames_bucket_total{bucket="3_10"} 2466
telemt_desync_frames_bucket_total{bucket="gt_10"} 2534
telemt_pool_swap_total 12
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2306
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2107
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 1567811
telemt_user_connections_current{user="hello"} 3766
telemt_user_octets_from_client{user="hello"} 23122056746 (21.53 GB)
telemt_user_octets_to_client{user="hello"} 501681005134 (467.23 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1320
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 18796.2 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1751672
telemt_connections_bad_total 210173
telemt_connections_current 2833
telemt_connections_me_current 2833
telemt_handshake_timeouts_total 18615
telemt_upstream_connect_attempt_total 2984
telemt_upstream_connect_success_total 2965
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2918
telemt_me_reconnect_success_total 2000
telemt_me_reader_eof_total 2029
telemt_me_idle_close_by_peer_total 2028
telemt_me_route_drop_no_conn_total 1556856
telemt_me_route_drop_channel_closed_total 94
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1329640
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4148
telemt_desync_full_logged_total 1240
telemt_desync_suppressed_total 2908
telemt_desync_frames_bucket_total{bucket="1_2"} 1082
telemt_desync_frames_bucket_total{bucket="3_10"} 1553
telemt_desync_frames_bucket_total{bucket="gt_10"} 1513
telemt_pool_swap_total 14
telemt_me_writer_close_signal_drop_total 45
telemt_me_writer_removed_unexpected_total 1989
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 1999
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1326643
telemt_user_connections_current{user="hello"} 2833
telemt_user_octets_from_client{user="hello"} 16837120612 (15.68 GB)
telemt_user_octets_to_client{user="hello"} 406869875828 (378.93 GB)
telemt_user_unique_ips_current{user="hello"} 975
telemt_user_unique_ips_recent_window{user="hello"} 394
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 18783.7 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1594023
telemt_connections_bad_total 58930
telemt_connections_current 2635
telemt_connections_me_current 2635
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 22312
telemt_upstream_connect_attempt_total 20235
telemt_upstream_connect_success_total 19302
telemt_upstream_connect_fail_total 933
telemt_upstream_connect_attempts_per_request{bucket="1"} 20235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 337
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 933
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4676
telemt_me_reconnect_success_total 2400
telemt_me_reader_eof_total 2487
telemt_me_idle_close_by_peer_total 2486
telemt_me_route_drop_no_conn_total 1385417
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1375490
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5495
telemt_desync_full_logged_total 1737
telemt_desync_suppressed_total 3758
telemt_desync_frames_bucket_total{bucket="1_2"} 1443
telemt_desync_frames_bucket_total{bucket="3_10"} 2021
telemt_desync_frames_bucket_total{bucket="gt_10"} 2031
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_removed_unexpected_total 2733
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2396
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 1390614
telemt_user_connections_current{user="hello"} 2635
telemt_user_octets_from_client{user="hello"} 25707001045 (23.94 GB)
telemt_user_octets_to_client{user="hello"} 304723683258 (283.80 GB)
telemt_user_msgs_from_client{user="hello"} 40382
telemt_user_msgs_to_client{user="hello"} 85113
telemt_user_unique_ips_current{user="hello"} 919
telemt_user_unique_ips_recent_window{user="hello"} 339
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 72507.3 (20h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5234286
telemt_connections_bad_total 919872
telemt_connections_current 3312
telemt_connections_me_current 3312
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 97487
telemt_upstream_connect_attempt_total 64629
telemt_upstream_connect_success_total 62138
telemt_upstream_connect_fail_total 2491
telemt_upstream_connect_attempts_per_request{bucket="1"} 64629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1041
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74730
telemt_me_reconnect_success_total 9324
telemt_me_reader_eof_total 9824
telemt_me_idle_close_by_peer_total 9821
telemt_me_route_drop_no_conn_total 2448673
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3665015
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
telemt_desync_total 15975
telemt_desync_full_logged_total 4870
telemt_desync_suppressed_total 11105
telemt_desync_frames_bucket_total{bucket="1_2"} 2621
telemt_desync_frames_bucket_total{bucket="3_10"} 6684
telemt_desync_frames_bucket_total{bucket="gt_10"} 6670
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 9564
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9300
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 3713130
telemt_user_connections_current{user="hello"} 3312
telemt_user_octets_from_client{user="hello"} 57869671683 (53.90 GB)
telemt_user_octets_to_client{user="hello"} 1359040499880 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1148
telemt_user_unique_ips_recent_window{user="hello"} 447
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 18749.4 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439750
telemt_connections_bad_total 29532
telemt_connections_current 830
telemt_connections_me_current 830
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 9288
telemt_upstream_connect_attempt_total 6746
telemt_upstream_connect_success_total 6550
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 6746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 539
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 382
telemt_me_reconnect_attempts_total 2651
telemt_me_reconnect_success_total 2600
telemt_me_reader_eof_total 2657
telemt_me_idle_close_by_peer_total 2656
telemt_me_route_drop_no_conn_total 256972
telemt_me_route_drop_channel_closed_total 92
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 346140
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 593
telemt_me_writer_pick_total{mode="p2c",result="full"} 5669
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 6328
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 990
telemt_desync_full_logged_total 307
telemt_desync_suppressed_total 683
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 400
telemt_desync_frames_bucket_total{bucket="gt_10"} 442
telemt_pool_swap_total 11
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 99
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 2601
telemt_me_writer_restored_same_endpoint_total 2591
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1099
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 364177
telemt_user_connections_current{user="hello"} 830
telemt_user_octets_from_client{user="hello"} 4475303372 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 81194839830 (75.62 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 298
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 18748.2 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1251091
telemt_connections_bad_total 83897
telemt_connections_current 3234
telemt_connections_me_current 3234
telemt_handshake_timeouts_total 22074
telemt_upstream_connect_attempt_total 3126
telemt_upstream_connect_success_total 3103
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 3126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 2157
telemt_me_reconnect_success_total 2132
telemt_me_reader_eof_total 2230
telemt_me_idle_close_by_peer_total 2230
telemt_me_route_drop_no_conn_total 485657
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1075153
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5878
telemt_desync_full_logged_total 1785
telemt_desync_suppressed_total 4093
telemt_desync_frames_bucket_total{bucket="1_2"} 1166
telemt_desync_frames_bucket_total{bucket="3_10"} 2030
telemt_desync_frames_bucket_total{bucket="gt_10"} 2682
telemt_pool_swap_total 15
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 2175
telemt_me_writer_restored_same_endpoint_total 2115
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 1074663
telemt_user_connections_current{user="hello"} 3234
telemt_user_octets_from_client{user="hello"} 16615310264 (15.47 GB)
telemt_user_octets_to_client{user="hello"} 469271259880 (437.04 GB)
telemt_user_unique_ips_current{user="hello"} 1029
telemt_user_unique_ips_recent_window{user="hello"} 395
```