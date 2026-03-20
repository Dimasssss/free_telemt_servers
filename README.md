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

# Server Metrics 2026-03-20 02:25:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 32855.1 (9h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 612634
telemt_connections_bad_total 38886
telemt_connections_current 797
telemt_connections_me_current 797
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10371
telemt_upstream_connect_attempt_total 6823
telemt_upstream_connect_success_total 6736
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 6823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4009
telemt_me_reconnect_success_total 3972
telemt_me_reader_eof_total 4194
telemt_me_idle_close_by_peer_total 4193
telemt_me_route_drop_no_conn_total 174535
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 488895
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2289
telemt_desync_full_logged_total 828
telemt_desync_suppressed_total 1461
telemt_desync_frames_bucket_total{bucket="1_2"} 467
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 1020
telemt_pool_swap_total 36
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4003
telemt_me_writer_restored_same_endpoint_total 3959
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 490328
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 30300391272 (28.22 GB)
telemt_user_octets_to_client{user="hello"} 171462191713 (159.69 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 49310.4 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3067861
telemt_connections_bad_total 139075
telemt_connections_current 1524
telemt_connections_me_current 1524
telemt_handshake_timeouts_total 67600
telemt_upstream_connect_attempt_total 9724
telemt_upstream_connect_success_total 9560
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 9724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10128
telemt_me_reconnect_success_total 5883
telemt_me_reader_eof_total 6293
telemt_me_idle_close_by_peer_total 6293
telemt_me_route_drop_no_conn_total 1517604
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2622921
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11270
telemt_desync_full_logged_total 3720
telemt_desync_suppressed_total 7550
telemt_desync_frames_bucket_total{bucket="1_2"} 2152
telemt_desync_frames_bucket_total{bucket="3_10"} 4406
telemt_desync_frames_bucket_total{bucket="gt_10"} 4712
telemt_pool_swap_total 42
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 52
telemt_me_writer_removed_unexpected_total 6082
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5828
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 2622693
telemt_user_connections_current{user="hello"} 1524
telemt_user_octets_from_client{user="hello"} 39978912122 (37.23 GB)
telemt_user_octets_to_client{user="hello"} 971900514078 (905.15 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 676
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 49288.4 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2999507
telemt_connections_bad_total 477159
telemt_connections_current 1182
telemt_connections_me_current 1182
telemt_handshake_timeouts_total 45520
telemt_upstream_connect_attempt_total 8020
telemt_upstream_connect_success_total 7962
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 8020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3908
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6447
telemt_me_reconnect_success_total 5513
telemt_me_reader_eof_total 5790
telemt_me_idle_close_by_peer_total 5789
telemt_me_route_drop_no_conn_total 1932986
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2070228
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7781
telemt_desync_full_logged_total 2372
telemt_desync_suppressed_total 5409
telemt_desync_frames_bucket_total{bucket="1_2"} 1908
telemt_desync_frames_bucket_total{bucket="3_10"} 2957
telemt_desync_frames_bucket_total{bucket="gt_10"} 2916
telemt_pool_swap_total 48
telemt_me_writer_close_signal_drop_total 70
telemt_me_writer_removed_unexpected_total 5567
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5512
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 2065852
telemt_user_connections_current{user="hello"} 1182
telemt_user_octets_from_client{user="hello"} 30390797148 (28.30 GB)
telemt_user_octets_to_client{user="hello"} 795284157768 (740.67 GB)
telemt_user_unique_ips_current{user="hello"} 489
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 49276.3 (13h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2647950
telemt_connections_bad_total 170153
telemt_connections_current 1219
telemt_connections_me_current 1219
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31652
telemt_upstream_connect_attempt_total 55883
telemt_upstream_connect_success_total 51589
telemt_upstream_connect_fail_total 4294
telemt_upstream_connect_attempts_per_request{bucket="1"} 55883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7693
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 530
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4294
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8741
telemt_me_reconnect_success_total 5892
telemt_me_reader_eof_total 6132
telemt_me_idle_close_by_peer_total 6131
telemt_me_route_drop_no_conn_total 1874777
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2173414
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8393
telemt_desync_full_logged_total 2661
telemt_desync_suppressed_total 5732
telemt_desync_frames_bucket_total{bucket="1_2"} 2067
telemt_desync_frames_bucket_total{bucket="3_10"} 3056
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 478
telemt_me_writer_removed_unexpected_total 6525
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5888
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 633
telemt_user_connections_total{user="hello"} 2215486
telemt_user_connections_current{user="hello"} 1219
telemt_user_octets_from_client{user="hello"} 35978413369 (33.51 GB)
telemt_user_octets_to_client{user="hello"} 625773464281 (582.80 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 102999.6 (28h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6324337
telemt_connections_bad_total 1049269
telemt_connections_current 1333
telemt_connections_me_current 1333
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 114415
telemt_upstream_connect_attempt_total 128005
telemt_upstream_connect_success_total 94718
telemt_upstream_connect_fail_total 33287
telemt_upstream_connect_attempts_per_request{bucket="1"} 128005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1435
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33287
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78933
telemt_me_reconnect_success_total 13262
telemt_me_reader_eof_total 14281
telemt_me_idle_close_by_peer_total 14267
telemt_me_route_drop_no_conn_total 2810916
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4489332
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
telemt_desync_total 19647
telemt_desync_full_logged_total 6228
telemt_desync_suppressed_total 13419
telemt_desync_frames_bucket_total{bucket="1_2"} 3460
telemt_desync_frames_bucket_total{bucket="3_10"} 8095
telemt_desync_frames_bucket_total{bucket="gt_10"} 8092
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 13571
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13237
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 4564548
telemt_user_connections_current{user="hello"} 1333
telemt_user_octets_from_client{user="hello"} 72875823800 (67.87 GB)
telemt_user_octets_to_client{user="hello"} 1754079122068 (1.60 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 578
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 49239.4 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 792862
telemt_connections_bad_total 79604
telemt_connections_current 521
telemt_connections_me_current 521
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13117
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 472120
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
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
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 649364
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 7486170143 (6.97 GB)
telemt_user_octets_to_client{user="hello"} 146564868558 (136.50 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 49241.0 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2067146
telemt_connections_bad_total 121547
telemt_connections_current 1244
telemt_connections_me_current 1244
telemt_handshake_timeouts_total 38171
telemt_upstream_connect_attempt_total 8846
telemt_upstream_connect_success_total 8785
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 8846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6370
telemt_me_reconnect_success_total 6325
telemt_me_reader_eof_total 6678
telemt_me_idle_close_by_peer_total 6678
telemt_me_route_drop_no_conn_total 752972
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1768541
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9320
telemt_desync_full_logged_total 3001
telemt_desync_suppressed_total 6319
telemt_desync_frames_bucket_total{bucket="1_2"} 1768
telemt_desync_frames_bucket_total{bucket="3_10"} 3265
telemt_desync_frames_bucket_total{bucket="gt_10"} 4287
telemt_pool_swap_total 49
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6418
telemt_me_writer_restored_same_endpoint_total 6308
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 1767649
telemt_user_connections_current{user="hello"} 1244
telemt_user_octets_from_client{user="hello"} 30170741400 (28.10 GB)
telemt_user_octets_to_client{user="hello"} 900816073336 (838.95 GB)
telemt_user_unique_ips_current{user="hello"} 501
telemt_user_unique_ips_recent_window{user="hello"} 97
```