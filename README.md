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

# Server Metrics 2026-03-22 22:43:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 92223.5 (25h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3334718
telemt_connections_bad_total 261584
telemt_connections_current 802
telemt_connections_me_current 802
telemt_handshake_timeouts_total 105080
telemt_upstream_connect_attempt_total 33940
telemt_upstream_connect_success_total 33939
telemt_upstream_connect_attempts_per_request{bucket="1"} 33939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1346
telemt_me_reconnect_success_total 556
telemt_me_reader_eof_total 572
telemt_me_idle_close_by_peer_total 572
telemt_me_route_drop_no_conn_total 2963223
telemt_me_route_drop_channel_closed_total 1227
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2793444
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 631
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 721
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 11946
telemt_desync_full_logged_total 3742
telemt_desync_suppressed_total 8204
telemt_desync_frames_bucket_total{bucket="1_2"} 3226
telemt_desync_frames_bucket_total{bucket="3_10"} 4367
telemt_desync_frames_bucket_total{bucket="gt_10"} 4353
telemt_pool_swap_total 102
telemt_pool_force_close_total 3173
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 631
telemt_me_draining_writers_reap_progress_total 31070
telemt_me_writer_removed_unexpected_total 552
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2258
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29032
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3118
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27897
telemt_me_writer_teardown_success_total{mode="normal"} 31290
telemt_me_writer_teardown_noop_total 31081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62371
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.582486
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62371
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 631
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 495
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2782769
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 39890664832 (37.15 GB)
telemt_user_octets_to_client{user="hello"} 754894983156 (703.05 GB)
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 105589.7 (29h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3952376
telemt_connections_bad_total 360297
telemt_connections_current 270
telemt_connections_me_current 270
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99857
telemt_upstream_connect_attempt_total 63634
telemt_upstream_connect_success_total 62853
telemt_upstream_connect_fail_total 691
telemt_upstream_connect_attempts_per_request{bucket="1"} 63544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 691
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9455
telemt_me_reconnect_success_total 3455
telemt_me_reader_eof_total 3474
telemt_me_idle_close_by_peer_total 3474
telemt_me_route_drop_no_conn_total 3635495
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3143316
telemt_me_endpoint_quarantine_total 786
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 816
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
telemt_me_writers_active_current 44
telemt_desync_total 12804
telemt_desync_full_logged_total 7176
telemt_desync_suppressed_total 5628
telemt_desync_frames_bucket_total{bucket="1_2"} 2893
telemt_desync_frames_bucket_total{bucket="3_10"} 5023
telemt_desync_frames_bucket_total{bucket="gt_10"} 4888
telemt_pool_swap_total 97
telemt_pool_force_close_total 2959
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 242
telemt_me_draining_writers_reap_progress_total 42405
telemt_me_writer_removed_unexpected_total 3410
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5816
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40026
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2501
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39446
telemt_me_writer_teardown_success_total{mode="normal"} 45842
telemt_me_writer_teardown_noop_total 42406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88248
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.510499
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88248
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 242
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 3124
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 3153955
telemt_user_connections_current{user="hello"} 270
telemt_user_octets_from_client{user="hello"} 42675808243 (39.74 GB)
telemt_user_octets_to_client{user="hello"} 778813043638 (725.33 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 180449.5 (50h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16209048
telemt_connections_bad_total 1608297
telemt_connections_current 1037
telemt_connections_me_current 1037
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396089
telemt_upstream_connect_attempt_total 80158
telemt_upstream_connect_success_total 80058
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 80075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1701
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2909
telemt_me_reconnect_success_total 1505
telemt_me_reader_eof_total 1452
telemt_me_idle_close_by_peer_total 1450
telemt_me_route_drop_no_conn_total 14030563
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12892909
telemt_me_endpoint_quarantine_total 1168
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1352
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_me_writers_active_current 42
telemt_desync_total 53316
telemt_desync_full_logged_total 16900
telemt_desync_suppressed_total 36416
telemt_desync_frames_bucket_total{bucket="1_2"} 11850
telemt_desync_frames_bucket_total{bucket="3_10"} 20756
telemt_desync_frames_bucket_total{bucket="gt_10"} 20710
telemt_pool_swap_total 195
telemt_pool_force_close_total 6509
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1046
telemt_me_draining_writers_reap_progress_total 59973
telemt_me_writer_removed_unexpected_total 1401
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5212
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55432
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6039
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53464
telemt_me_writer_teardown_success_total{mode="normal"} 60644
telemt_me_writer_teardown_noop_total 60026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120670
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 316.938233
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120670
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1046
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1302
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 12893139
telemt_user_connections_current{user="hello"} 1037
telemt_user_octets_from_client{user="hello"} 190012095341 (176.96 GB)
telemt_user_octets_to_client{user="hello"} 3463807059427 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 180450.9 (50h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11766839
telemt_connections_bad_total 1209362
telemt_connections_current 784
telemt_connections_me_current 784
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343997
telemt_upstream_connect_attempt_total 94626
telemt_upstream_connect_success_total 93315
telemt_upstream_connect_fail_total 864
telemt_upstream_connect_attempts_per_request{bucket="1"} 94179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38740
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3794
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 864
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4320
telemt_me_reconnect_success_total 1810
telemt_me_reader_eof_total 1671
telemt_me_idle_close_by_peer_total 1671
telemt_me_route_drop_no_conn_total 4543922
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8749669
telemt_me_endpoint_quarantine_total 1172
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1373
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 38611
telemt_desync_full_logged_total 12989
telemt_desync_suppressed_total 25622
telemt_desync_frames_bucket_total{bucket="1_2"} 9539
telemt_desync_frames_bucket_total{bucket="3_10"} 14841
telemt_desync_frames_bucket_total{bucket="gt_10"} 14231
telemt_pool_swap_total 192
telemt_pool_force_close_total 5878
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 58315
telemt_me_writer_removed_unexpected_total 1706
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5326
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54546
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5366
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52437
telemt_me_writer_teardown_success_total{mode="normal"} 59872
telemt_me_writer_teardown_noop_total 58340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118212
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.262634
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118212
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1542
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8687494
telemt_user_connections_current{user="hello"} 784
telemt_user_octets_from_client{user="hello"} 217322293592 (202.40 GB)
telemt_user_octets_to_client{user="hello"} 3935412171739 (3.58 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 180415.9 (50h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10968189
telemt_connections_bad_total 955589
telemt_connections_current 529
telemt_connections_me_current 529
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344993
telemt_upstream_connect_attempt_total 78710
telemt_upstream_connect_success_total 77170
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 77375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1985
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2349
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5644
telemt_me_reconnect_success_total 2294
telemt_me_reader_eof_total 2034
telemt_me_idle_close_by_peer_total 2033
telemt_me_route_drop_no_conn_total 5326099
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8300861
telemt_me_endpoint_quarantine_total 1248
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1327
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_me_writers_active_current 42
telemt_desync_total 37882
telemt_desync_full_logged_total 12563
telemt_desync_suppressed_total 25319
telemt_desync_frames_bucket_total{bucket="1_2"} 9569
telemt_desync_frames_bucket_total{bucket="3_10"} 14493
telemt_desync_frames_bucket_total{bucket="gt_10"} 13820
telemt_pool_swap_total 188
telemt_pool_force_close_total 5794
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 733
telemt_me_draining_writers_reap_progress_total 58534
telemt_me_writer_removed_unexpected_total 2188
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6056
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54594
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5223
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52740
telemt_me_writer_teardown_success_total{mode="normal"} 60650
telemt_me_writer_teardown_noop_total 58605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119255
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.617069
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119255
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 733
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 1985
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8292849
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 192129775945 (178.93 GB)
telemt_user_octets_to_client{user="hello"} 3449714696545 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 50695.3 (14h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11101172
telemt_connections_bad_total 667102
telemt_connections_current 975
telemt_connections_me_current 975
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 254224
telemt_upstream_connect_attempt_total 53152
telemt_upstream_connect_success_total 50382
telemt_upstream_connect_fail_total 1885
telemt_upstream_connect_attempts_per_request{bucket="1"} 52267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16725
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5998
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1885
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7282
telemt_me_reconnect_success_total 1101
telemt_me_reader_eof_total 677
telemt_me_idle_close_by_peer_total 676
telemt_me_route_drop_no_conn_total 25267121
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9221006
telemt_me_endpoint_quarantine_total 358
telemt_me_single_endpoint_outage_enter_total 84
telemt_me_single_endpoint_outage_exit_total 84
telemt_me_single_endpoint_outage_reconnect_attempt_total 157
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 157
telemt_me_single_endpoint_shadow_rotate_total 405
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 38
telemt_desync_total 15846
telemt_desync_full_logged_total 4224
telemt_desync_suppressed_total 11622
telemt_desync_frames_bucket_total{bucket="1_2"} 3028
telemt_desync_frames_bucket_total{bucket="3_10"} 6406
telemt_desync_frames_bucket_total{bucket="gt_10"} 6412
telemt_pool_swap_total 52
telemt_pool_force_close_total 1791
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 462
telemt_me_draining_writers_reap_progress_total 15087
telemt_me_writer_removed_unexpected_total 995
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2197
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13837
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1484
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13296
telemt_me_writer_teardown_success_total{mode="normal"} 16034
telemt_me_writer_teardown_noop_total 15106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31140
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.669236
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31140
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 462
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 711
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 9246517
telemt_user_connections_current{user="hello"} 975
telemt_user_octets_from_client{user="hello"} 86003454922 (80.10 GB)
telemt_user_octets_to_client{user="hello"} 573670286865 (534.27 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 180421.8 (50h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10897732
telemt_connections_bad_total 927845
telemt_connections_current 871
telemt_connections_me_current 871
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 239527
telemt_upstream_connect_attempt_total 107503
telemt_upstream_connect_success_total 106384
telemt_upstream_connect_fail_total 949
telemt_upstream_connect_attempts_per_request{bucket="1"} 107333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 949
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72740
telemt_me_reconnect_success_total 2974
telemt_me_reader_eof_total 2671
telemt_me_idle_close_by_peer_total 2669
telemt_me_route_drop_no_conn_total 5246251
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8606785
telemt_me_endpoint_quarantine_total 1191
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1357
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 45918
telemt_desync_full_logged_total 15706
telemt_desync_suppressed_total 30212
telemt_desync_frames_bucket_total{bucket="1_2"} 9309
telemt_desync_frames_bucket_total{bucket="3_10"} 17574
telemt_desync_frames_bucket_total{bucket="gt_10"} 19035
telemt_pool_swap_total 184
telemt_pool_force_close_total 5483
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 654
telemt_me_draining_writers_reap_progress_total 62551
telemt_me_writer_removed_unexpected_total 2703
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6571
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58715
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4734
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57068
telemt_me_writer_teardown_success_total{mode="normal"} 65286
telemt_me_writer_teardown_noop_total 62552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127838
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.185355
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127838
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 654
telemt_me_refill_failed_total 4296
telemt_me_writer_restored_same_endpoint_total 2512
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8609859
telemt_user_connections_current{user="hello"} 871
telemt_user_octets_from_client{user="hello"} 193914460785 (180.60 GB)
telemt_user_octets_to_client{user="hello"} 3287075962080 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 117257.9 (32h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11564131
telemt_connections_bad_total 461919
telemt_connections_current 625
telemt_connections_me_current 625
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4738698
telemt_upstream_connect_attempt_total 55598
telemt_upstream_connect_success_total 55188
telemt_upstream_connect_fail_total 399
telemt_upstream_connect_attempts_per_request{bucket="1"} 55587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 399
telemt_me_reconnect_attempts_total 48717
telemt_me_reconnect_success_total 1735
telemt_me_reader_eof_total 1399
telemt_me_idle_close_by_peer_total 1398
telemt_me_route_drop_no_conn_total 4075221
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5563589
telemt_me_endpoint_quarantine_total 767
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 892
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31297
telemt_desync_full_logged_total 10654
telemt_desync_suppressed_total 20643
telemt_desync_frames_bucket_total{bucket="1_2"} 6209
telemt_desync_frames_bucket_total{bucket="3_10"} 12354
telemt_desync_frames_bucket_total{bucket="gt_10"} 12734
telemt_pool_swap_total 124
telemt_pool_force_close_total 3726
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 41582
telemt_me_writer_removed_unexpected_total 1453
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3554
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39521
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3285
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37856
telemt_me_writer_teardown_success_total{mode="normal"} 43075
telemt_me_writer_teardown_noop_total 41589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84664
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.636844
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84664
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 2730
telemt_me_writer_restored_same_endpoint_total 1539
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5556204
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 118582821256 (110.44 GB)
telemt_user_octets_to_client{user="hello"} 2147197617386 (1.95 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 98228.7 (27h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1466681
telemt_connections_bad_total 36400
telemt_connections_current 565
telemt_connections_me_current 565
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29211
telemt_upstream_connect_attempt_total 45959
telemt_upstream_connect_success_total 45814
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 45931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 767
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2112
telemt_me_reconnect_success_total 863
telemt_me_reader_eof_total 842
telemt_me_idle_close_by_peer_total 842
telemt_me_route_drop_no_conn_total 505863
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1301579
telemt_me_endpoint_quarantine_total 797
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 806
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 8215
telemt_desync_full_logged_total 2482
telemt_desync_suppressed_total 5733
telemt_desync_frames_bucket_total{bucket="1_2"} 2053
telemt_desync_frames_bucket_total{bucket="3_10"} 3176
telemt_desync_frames_bucket_total{bucket="gt_10"} 2986
telemt_pool_swap_total 106
telemt_pool_force_close_total 2736
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 151
telemt_me_draining_writers_reap_progress_total 38524
telemt_me_writer_removed_unexpected_total 815
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3021
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36352
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2648
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35788
telemt_me_writer_teardown_success_total{mode="normal"} 39373
telemt_me_writer_teardown_noop_total 38528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77901
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.986957
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77901
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 151
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 733
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 1297483
telemt_user_connections_current{user="hello"} 565
telemt_user_octets_from_client{user="hello"} 25475429585 (23.73 GB)
telemt_user_octets_to_client{user="hello"} 554141591295 (516.08 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 180426.2 (50h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13220415
telemt_connections_bad_total 1567650
telemt_connections_current 829
telemt_connections_me_current 829
telemt_handshake_timeouts_total 380430
telemt_upstream_connect_attempt_total 69210
telemt_upstream_connect_success_total 68870
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 69074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2709
telemt_me_reconnect_success_total 1398
telemt_me_reader_eof_total 1372
telemt_me_idle_close_by_peer_total 1372
telemt_me_route_drop_no_conn_total 4472520
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9993677
telemt_me_endpoint_quarantine_total 1237
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1357
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 41760
telemt_desync_full_logged_total 13628
telemt_desync_suppressed_total 28132
telemt_desync_frames_bucket_total{bucket="1_2"} 10038
telemt_desync_frames_bucket_total{bucket="3_10"} 15368
telemt_desync_frames_bucket_total{bucket="gt_10"} 16354
telemt_pool_swap_total 200
telemt_pool_force_close_total 5440
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 62464
telemt_me_writer_removed_unexpected_total 1317
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5023
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58803
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5266
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57024
telemt_me_writer_teardown_success_total{mode="normal"} 63826
telemt_me_writer_teardown_noop_total 62466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 123718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126292
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.616689
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126292
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 1224
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 9960443
telemt_user_connections_current{user="hello"} 829
telemt_user_octets_from_client{user="hello"} 194194637772 (180.86 GB)
telemt_user_octets_to_client{user="hello"} 4416122006744 (4.02 TB)
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 180422.8 (50h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11517692
telemt_connections_bad_total 1316965
telemt_connections_current 718
telemt_connections_me_current 718
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 305524
telemt_upstream_connect_attempt_total 95770
telemt_upstream_connect_success_total 94918
telemt_upstream_connect_fail_total 645
telemt_upstream_connect_attempts_per_request{bucket="1"} 95563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40212
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 645
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10110
telemt_me_reconnect_success_total 2461
telemt_me_reader_eof_total 2295
telemt_me_idle_close_by_peer_total 2294
telemt_me_seq_mismatch_total 86
telemt_me_route_drop_no_conn_total 5632959
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8895251
telemt_me_endpoint_quarantine_total 1407
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1360
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
telemt_me_writers_active_current 46
telemt_desync_total 41397
telemt_desync_full_logged_total 13284
telemt_desync_suppressed_total 28113
telemt_desync_frames_bucket_total{bucket="1_2"} 10637
telemt_desync_frames_bucket_total{bucket="3_10"} 15230
telemt_desync_frames_bucket_total{bucket="gt_10"} 15530
telemt_pool_swap_total 190
telemt_pool_force_close_total 5231
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 62275
telemt_me_writer_removed_unexpected_total 2330
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6377
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58308
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4760
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57044
telemt_me_writer_teardown_success_total{mode="normal"} 64685
telemt_me_writer_teardown_noop_total 62280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126965
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.327680
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126965
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 395
telemt_me_writer_restored_same_endpoint_total 1996
telemt_me_writer_restored_fallback_total 118
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 8900648
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 156868641601 (146.10 GB)
telemt_user_octets_to_client{user="hello"} 3464589973535 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 79
```