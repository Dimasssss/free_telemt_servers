# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-23 03:28:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 109314.7 (30h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3732424
telemt_connections_bad_total 360950
telemt_connections_current 1052
telemt_connections_me_current 1052
telemt_handshake_timeouts_total 121452
telemt_upstream_connect_attempt_total 40809
telemt_upstream_connect_success_total 40808
telemt_upstream_connect_attempts_per_request{bucket="1"} 40808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26454
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1436
telemt_me_reconnect_success_total 635
telemt_me_reader_eof_total 653
telemt_me_idle_close_by_peer_total 653
telemt_me_route_drop_no_conn_total 3014449
telemt_me_route_drop_channel_closed_total 1239
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3047494
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 778
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 855
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 13083
telemt_desync_full_logged_total 4155
telemt_desync_suppressed_total 8928
telemt_desync_frames_bucket_total{bucket="1_2"} 3464
telemt_desync_frames_bucket_total{bucket="3_10"} 4790
telemt_desync_frames_bucket_total{bucket="gt_10"} 4829
telemt_pool_swap_total 121
telemt_pool_force_close_total 3689
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 676
telemt_me_draining_writers_reap_progress_total 37365
telemt_me_writer_removed_unexpected_total 630
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2662
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34981
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3633
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33676
telemt_me_writer_teardown_success_total{mode="normal"} 37643
telemt_me_writer_teardown_noop_total 37376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75019
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.702684
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75019
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 676
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 570
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 3036358
telemt_user_connections_current{user="hello"} 1052
telemt_user_octets_from_client{user="hello"} 42986937136 (40.03 GB)
telemt_user_octets_to_client{user="hello"} 826649316584 (769.88 GB)
telemt_user_unique_ips_current{user="hello"} 485
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 122680.6 (34h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4053689
telemt_connections_bad_total 375472
telemt_connections_current 331
telemt_connections_me_current 331
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 102295
telemt_upstream_connect_attempt_total 77206
telemt_upstream_connect_success_total 76281
telemt_upstream_connect_fail_total 818
telemt_upstream_connect_attempts_per_request{bucket="1"} 77099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 818
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10521
telemt_me_reconnect_success_total 3753
telemt_me_reader_eof_total 3735
telemt_me_idle_close_by_peer_total 3735
telemt_me_route_drop_no_conn_total 3648473
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3218637
telemt_me_endpoint_quarantine_total 995
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 967
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 13135
telemt_desync_full_logged_total 7379
telemt_desync_suppressed_total 5756
telemt_desync_frames_bucket_total{bucket="1_2"} 2985
telemt_desync_frames_bucket_total{bucket="3_10"} 5150
telemt_desync_frames_bucket_total{bucket="gt_10"} 5000
telemt_pool_swap_total 116
telemt_pool_force_close_total 3223
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 51098
telemt_me_writer_removed_unexpected_total 3659
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6561
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48235
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2765
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47875
telemt_me_writer_teardown_success_total{mode="normal"} 54796
telemt_me_writer_teardown_noop_total 51099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105895
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.692897
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105895
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 265
telemt_me_writer_restored_same_endpoint_total 3326
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 3233113
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 43451915927 (40.47 GB)
telemt_user_octets_to_client{user="hello"} 804315039569 (749.08 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 197540.6 (54h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16461941
telemt_connections_bad_total 1669970
telemt_connections_current 1051
telemt_connections_me_current 1051
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 400199
telemt_upstream_connect_attempt_total 89026
telemt_upstream_connect_success_total 88919
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 88936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1725
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3080
telemt_me_reconnect_success_total 1637
telemt_me_reader_eof_total 1590
telemt_me_idle_close_by_peer_total 1588
telemt_me_route_drop_no_conn_total 14065401
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13068866
telemt_me_endpoint_quarantine_total 1327
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1493
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 54337
telemt_desync_full_logged_total 17303
telemt_desync_suppressed_total 37034
telemt_desync_frames_bucket_total{bucket="1_2"} 12115
telemt_desync_frames_bucket_total{bucket="3_10"} 21225
telemt_desync_frames_bucket_total{bucket="gt_10"} 20997
telemt_pool_swap_total 214
telemt_pool_force_close_total 6925
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1073
telemt_me_draining_writers_reap_progress_total 68091
telemt_me_writer_removed_unexpected_total 1526
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5736
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63164
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6455
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61166
telemt_me_writer_teardown_success_total{mode="normal"} 68900
telemt_me_writer_teardown_noop_total 68144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137044
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.025478
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137044
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1073
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1419
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 13068815
telemt_user_connections_current{user="hello"} 1051
telemt_user_octets_from_client{user="hello"} 198113302569 (184.51 GB)
telemt_user_octets_to_client{user="hello"} 3527988725607 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 509
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 197541.9 (54h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12001384
telemt_connections_bad_total 1261197
telemt_connections_current 690
telemt_connections_me_current 690
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 345990
telemt_upstream_connect_attempt_total 103302
telemt_upstream_connect_success_total 101961
telemt_upstream_connect_fail_total 888
telemt_upstream_connect_attempts_per_request{bucket="1"} 102849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43611
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 888
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4554
telemt_me_reconnect_success_total 1952
telemt_me_reader_eof_total 1819
telemt_me_idle_close_by_peer_total 1819
telemt_me_route_drop_no_conn_total 4570718
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8889609
telemt_me_endpoint_quarantine_total 1347
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1513
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 39128
telemt_desync_full_logged_total 13182
telemt_desync_suppressed_total 25946
telemt_desync_frames_bucket_total{bucket="1_2"} 9688
telemt_desync_frames_bucket_total{bucket="3_10"} 15032
telemt_desync_frames_bucket_total{bucket="gt_10"} 14408
telemt_pool_swap_total 211
telemt_pool_force_close_total 6271
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 66202
telemt_me_writer_removed_unexpected_total 1846
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5827
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62080
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5759
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59931
telemt_me_writer_teardown_success_total{mode="normal"} 67907
telemt_me_writer_teardown_noop_total 66227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134134
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.560859
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134134
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 1670
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8827308
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 218489527828 (203.48 GB)
telemt_user_octets_to_client{user="hello"} 3987284341355 (3.63 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 197505.9 (54h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11154312
telemt_connections_bad_total 1001745
telemt_connections_current 609
telemt_connections_me_current 609
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 347083
telemt_upstream_connect_attempt_total 87745
telemt_upstream_connect_success_total 86179
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 86384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42170
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5823
telemt_me_reconnect_success_total 2426
telemt_me_reader_eof_total 2175
telemt_me_idle_close_by_peer_total 2174
telemt_me_route_drop_no_conn_total 5349325
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8413827
telemt_me_endpoint_quarantine_total 1388
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1472
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 38357
telemt_desync_full_logged_total 12720
telemt_desync_suppressed_total 25637
telemt_desync_frames_bucket_total{bucket="1_2"} 9688
telemt_desync_frames_bucket_total{bucket="3_10"} 14691
telemt_desync_frames_bucket_total{bucket="gt_10"} 13978
telemt_pool_swap_total 207
telemt_pool_force_close_total 6166
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 751
telemt_me_draining_writers_reap_progress_total 66767
telemt_me_writer_removed_unexpected_total 2321
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6564
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62460
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5595
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60601
telemt_me_writer_teardown_success_total{mode="normal"} 69024
telemt_me_writer_teardown_noop_total 66838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135862
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.890506
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135862
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 751
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2113
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 8405718
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 193205720175 (179.94 GB)
telemt_user_octets_to_client{user="hello"} 3489957803477 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 67785.9 (18h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11398948
telemt_connections_bad_total 672226
telemt_connections_current 1141
telemt_connections_me_current 1141
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 291590
telemt_upstream_connect_attempt_total 63084
telemt_upstream_connect_success_total 59719
telemt_upstream_connect_fail_total 2197
telemt_upstream_connect_attempts_per_request{bucket="1"} 61916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2197
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8086
telemt_me_reconnect_success_total 1405
telemt_me_reader_eof_total 891
telemt_me_idle_close_by_peer_total 890
telemt_me_route_drop_no_conn_total 25314411
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9449496
telemt_me_endpoint_quarantine_total 526
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 547
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 16749
telemt_desync_full_logged_total 4598
telemt_desync_suppressed_total 12151
telemt_desync_frames_bucket_total{bucket="1_2"} 3199
telemt_desync_frames_bucket_total{bucket="3_10"} 6832
telemt_desync_frames_bucket_total{bucket="gt_10"} 6718
telemt_pool_swap_total 70
telemt_pool_force_close_total 2211
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 503
telemt_me_draining_writers_reap_progress_total 22315
telemt_me_writer_removed_unexpected_total 1288
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2913
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20638
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1890
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 321
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20104
telemt_me_writer_teardown_success_total{mode="normal"} 23551
telemt_me_writer_teardown_noop_total 22334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45885
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.116456
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45885
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 503
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 906
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 367
telemt_user_connections_total{user="hello"} 9476020
telemt_user_connections_current{user="hello"} 1141
telemt_user_octets_from_client{user="hello"} 88060919790 (82.01 GB)
telemt_user_octets_to_client{user="hello"} 646654113781 (602.24 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 444
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 197512.3 (54h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11107568
telemt_connections_bad_total 968272
telemt_connections_current 1027
telemt_connections_me_current 1027
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 244782
telemt_upstream_connect_attempt_total 116539
telemt_upstream_connect_success_total 115346
telemt_upstream_connect_fail_total 1018
telemt_upstream_connect_attempts_per_request{bucket="1"} 116364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1370
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1018
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73213
telemt_me_reconnect_success_total 3175
telemt_me_reader_eof_total 2874
telemt_me_idle_close_by_peer_total 2871
telemt_me_route_drop_no_conn_total 5279978
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8754661
telemt_me_endpoint_quarantine_total 1344
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1500
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 46616
telemt_desync_full_logged_total 16003
telemt_desync_suppressed_total 30613
telemt_desync_frames_bucket_total{bucket="1_2"} 9471
telemt_desync_frames_bucket_total{bucket="3_10"} 17850
telemt_desync_frames_bucket_total{bucket="gt_10"} 19295
telemt_pool_swap_total 203
telemt_pool_force_close_total 5887
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 674
telemt_me_draining_writers_reap_progress_total 70756
telemt_me_writer_removed_unexpected_total 2893
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7115
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66579
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5138
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64869
telemt_me_writer_teardown_success_total{mode="normal"} 73694
telemt_me_writer_teardown_noop_total 70757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 142296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 143715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 144134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 144407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 144441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144451
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.324878
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144451
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 674
telemt_me_refill_failed_total 4310
telemt_me_writer_restored_same_endpoint_total 2677
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 8757513
telemt_user_connections_current{user="hello"} 1027
telemt_user_octets_from_client{user="hello"} 196686425893 (183.18 GB)
telemt_user_octets_to_client{user="hello"} 3347389147916 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 134348.7 (37h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11837182
telemt_connections_bad_total 484920
telemt_connections_current 651
telemt_connections_me_current 651
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4794571
telemt_upstream_connect_attempt_total 65329
telemt_upstream_connect_success_total 64856
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 65316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_reconnect_attempts_total 49201
telemt_me_reconnect_success_total 1919
telemt_me_reader_eof_total 1597
telemt_me_idle_close_by_peer_total 1596
telemt_me_route_drop_no_conn_total 4108010
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5686634
telemt_me_endpoint_quarantine_total 925
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1035
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31919
telemt_desync_full_logged_total 10916
telemt_desync_suppressed_total 21003
telemt_desync_frames_bucket_total{bucket="1_2"} 6372
telemt_desync_frames_bucket_total{bucket="3_10"} 12594
telemt_desync_frames_bucket_total{bucket="gt_10"} 12953
telemt_pool_swap_total 143
telemt_pool_force_close_total 4087
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 385
telemt_me_draining_writers_reap_progress_total 50443
telemt_me_writer_removed_unexpected_total 1640
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4059
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48075
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3643
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46356
telemt_me_writer_teardown_success_total{mode="normal"} 52134
telemt_me_writer_teardown_noop_total 50450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102584
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.759288
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102584
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 385
telemt_me_refill_failed_total 2747
telemt_me_writer_restored_same_endpoint_total 1696
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5678699
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 120552584600 (112.27 GB)
telemt_user_octets_to_client{user="hello"} 2210941978910 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 115319.5 (32h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1586640
telemt_connections_bad_total 37013
telemt_connections_current 545
telemt_connections_me_current 545
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32662
telemt_upstream_connect_attempt_total 54623
telemt_upstream_connect_success_total 54453
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 54595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 807
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2369
telemt_me_reconnect_success_total 966
telemt_me_reader_eof_total 957
telemt_me_idle_close_by_peer_total 957
telemt_me_route_drop_no_conn_total 532362
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1410630
telemt_me_endpoint_quarantine_total 983
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 952
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 9912
telemt_desync_full_logged_total 2800
telemt_desync_suppressed_total 7112
telemt_desync_frames_bucket_total{bucket="1_2"} 3095
telemt_desync_frames_bucket_total{bucket="3_10"} 3745
telemt_desync_frames_bucket_total{bucket="gt_10"} 3072
telemt_pool_swap_total 125
telemt_pool_force_close_total 3122
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 46455
telemt_me_writer_removed_unexpected_total 922
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3512
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43907
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3034
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43333
telemt_me_writer_teardown_success_total{mode="normal"} 47419
telemt_me_writer_teardown_noop_total 46459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93878
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.500059
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93878
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 824
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 1406354
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 26570837041 (24.75 GB)
telemt_user_octets_to_client{user="hello"} 591477046187 (550.86 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 197517.0 (54h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13423723
telemt_connections_bad_total 1627102
telemt_connections_current 862
telemt_connections_me_current 862
telemt_handshake_timeouts_total 391690
telemt_upstream_connect_attempt_total 79216
telemt_upstream_connect_success_total 78860
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 79080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3089
telemt_me_reconnect_success_total 1564
telemt_me_reader_eof_total 1551
telemt_me_idle_close_by_peer_total 1551
telemt_me_route_drop_no_conn_total 4495125
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10109856
telemt_me_endpoint_quarantine_total 1448
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1499
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 42423
telemt_desync_full_logged_total 13857
telemt_desync_suppressed_total 28566
telemt_desync_frames_bucket_total{bucket="1_2"} 10331
telemt_desync_frames_bucket_total{bucket="3_10"} 15580
telemt_desync_frames_bucket_total{bucket="gt_10"} 16512
telemt_pool_swap_total 219
telemt_pool_force_close_total 5746
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 687
telemt_me_draining_writers_reap_progress_total 71693
telemt_me_writer_removed_unexpected_total 1485
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5551
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67683
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5572
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65947
telemt_me_writer_teardown_success_total{mode="normal"} 73234
telemt_me_writer_teardown_noop_total 71695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 142308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 144037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 144420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 144796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 144916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144929
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.862113
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144929
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 687
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1377
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10076477
telemt_user_connections_current{user="hello"} 862
telemt_user_octets_from_client{user="hello"} 195364380928 (181.95 GB)
telemt_user_octets_to_client{user="hello"} 4481205985564 (4.08 TB)
telemt_user_unique_ips_current{user="hello"} 380
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 197513.4 (54h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11736207
telemt_connections_bad_total 1374656
telemt_connections_current 731
telemt_connections_me_current 731
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 314607
telemt_upstream_connect_attempt_total 106878
telemt_upstream_connect_success_total 105957
telemt_upstream_connect_fail_total 713
telemt_upstream_connect_attempts_per_request{bucket="1"} 106670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45389
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2069
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 713
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10803
telemt_me_reconnect_success_total 2674
telemt_me_reader_eof_total 2483
telemt_me_idle_close_by_peer_total 2482
telemt_me_seq_mismatch_total 103
telemt_me_route_drop_no_conn_total 5663345
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9028591
telemt_me_endpoint_quarantine_total 1620
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1503
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 42132
telemt_desync_full_logged_total 13566
telemt_desync_suppressed_total 28566
telemt_desync_frames_bucket_total{bucket="1_2"} 10947
telemt_desync_frames_bucket_total{bucket="3_10"} 15482
telemt_desync_frames_bucket_total{bucket="gt_10"} 15703
telemt_pool_swap_total 209
telemt_pool_force_close_total 5511
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 71885
telemt_me_writer_removed_unexpected_total 2518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6928
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67572
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5040
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66374
telemt_me_writer_teardown_success_total{mode="normal"} 74500
telemt_me_writer_teardown_noop_total 71890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 143686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 145482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 146021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 146340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 146390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 146390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 146390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 146390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 146390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 146390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 146390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 146390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 146390
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.585105
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 146390
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 421
telemt_me_writer_restored_same_endpoint_total 2139
telemt_me_writer_restored_fallback_total 139
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 9033140
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 158003678580 (147.15 GB)
telemt_user_octets_to_client{user="hello"} 3524499599458 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 97
```