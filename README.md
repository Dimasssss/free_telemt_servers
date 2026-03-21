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

# Server Metrics 2026-03-21 20:28:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 85961.0 (23h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3068730
telemt_connections_bad_total 179345
telemt_connections_current 982
telemt_connections_me_current 982
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 94523
telemt_upstream_connect_attempt_total 35135
telemt_upstream_connect_success_total 34989
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 35092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20820
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 56
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1887
telemt_me_reconnect_success_total 760
telemt_me_reader_eof_total 728
telemt_me_idle_close_by_peer_total 728
telemt_me_route_drop_no_conn_total 2620894
telemt_me_route_drop_channel_closed_total 843
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2483079
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 584
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 671
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_active_current 46
telemt_desync_total 9940
telemt_desync_full_logged_total 3466
telemt_desync_suppressed_total 6474
telemt_desync_frames_bucket_total{bucket="1_2"} 2165
telemt_desync_frames_bucket_total{bucket="3_10"} 3732
telemt_desync_frames_bucket_total{bucket="gt_10"} 4043
telemt_pool_swap_total 93
telemt_pool_force_close_total 2814
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 28810
telemt_me_writer_removed_unexpected_total 710
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2421
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26839
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2675
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 139
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25996
telemt_me_writer_teardown_success_total{mode="normal"} 29260
telemt_me_writer_teardown_noop_total 28818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58078
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 300.058557
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58078
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 653
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 2482699
telemt_user_connections_current{user="hello"} 982
telemt_user_octets_from_client{user="hello"} 36805180809 (34.28 GB)
telemt_user_octets_to_client{user="hello"} 631609663470 (588.23 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 394
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 11098.9 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 446891
telemt_connections_bad_total 20210
telemt_connections_current 884
telemt_connections_me_current 884
telemt_handshake_timeouts_total 15685
telemt_upstream_connect_attempt_total 4438
telemt_upstream_connect_success_total 4347
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 4426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_reconnect_attempts_total 307
telemt_me_reconnect_success_total 142
telemt_me_reader_eof_total 120
telemt_me_idle_close_by_peer_total 120
telemt_me_route_drop_no_conn_total 269703
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364979
telemt_me_endpoint_quarantine_total 86
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 92
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 1549
telemt_desync_full_logged_total 880
telemt_desync_suppressed_total 669
telemt_desync_frames_bucket_total{bucket="1_2"} 312
telemt_desync_frames_bucket_total{bucket="3_10"} 589
telemt_desync_frames_bucket_total{bucket="gt_10"} 648
telemt_pool_swap_total 12
telemt_pool_force_close_total 363
telemt_me_writer_close_signal_drop_total 32
telemt_me_draining_writers_reap_progress_total 3849
telemt_me_writer_removed_unexpected_total 113
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 334
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3622
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 356
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3486
telemt_me_writer_teardown_success_total{mode="normal"} 3956
telemt_me_writer_teardown_noop_total 3849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7805
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.106301
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7805
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 32
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 95
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 364547
telemt_user_connections_current{user="hello"} 884
telemt_user_octets_from_client{user="hello"} 5938986928 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 106884094308 (99.54 GB)
telemt_user_unique_ips_current{user="hello"} 565
telemt_user_unique_ips_recent_window{user="hello"} 335
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 85958.7 (23h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6840635
telemt_connections_bad_total 526727
telemt_connections_current 3433
telemt_connections_me_current 3433
telemt_handshake_timeouts_total 213860
telemt_upstream_connect_attempt_total 30882
telemt_upstream_connect_success_total 30820
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 30826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1325
telemt_me_reconnect_success_total 666
telemt_me_reader_eof_total 675
telemt_me_idle_close_by_peer_total 675
telemt_me_route_drop_no_conn_total 4341199
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5604682
telemt_me_endpoint_quarantine_total 532
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 639
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 23090
telemt_desync_full_logged_total 7681
telemt_desync_suppressed_total 15409
telemt_desync_frames_bucket_total{bucket="1_2"} 4832
telemt_desync_frames_bucket_total{bucket="3_10"} 9178
telemt_desync_frames_bucket_total{bucket="gt_10"} 9080
telemt_pool_swap_total 92
telemt_pool_force_close_total 3091
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 500
telemt_me_draining_writers_reap_progress_total 28117
telemt_me_writer_removed_unexpected_total 649
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2417
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25980
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2861
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25026
telemt_me_writer_teardown_success_total{mode="normal"} 28397
telemt_me_writer_teardown_noop_total 28154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56551
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 137.920712
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56551
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 500
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 597
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 5597932
telemt_user_connections_current{user="hello"} 3433
telemt_user_octets_from_client{user="hello"} 93749325636 (87.31 GB)
telemt_user_octets_to_client{user="hello"} 1756814388316 (1.60 TB)
telemt_user_unique_ips_current{user="hello"} 1380
telemt_user_unique_ips_recent_window{user="hello"} 433
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 85960.2 (23h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5540093
telemt_connections_bad_total 537392
telemt_connections_current 3160
telemt_connections_me_current 3160
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 182358
telemt_upstream_connect_attempt_total 34993
telemt_upstream_connect_success_total 34675
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 34839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16549
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 541
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1665
telemt_me_reconnect_success_total 692
telemt_me_reader_eof_total 666
telemt_me_idle_close_by_peer_total 666
telemt_me_route_drop_no_conn_total 1920030
telemt_me_route_drop_channel_closed_total 220
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4146674
telemt_me_endpoint_quarantine_total 528
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 656
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
telemt_me_writers_active_current 43
telemt_desync_total 19680
telemt_desync_full_logged_total 6509
telemt_desync_suppressed_total 13171
telemt_desync_frames_bucket_total{bucket="1_2"} 4818
telemt_desync_frames_bucket_total{bucket="3_10"} 7624
telemt_desync_frames_bucket_total{bucket="gt_10"} 7238
telemt_pool_swap_total 94
telemt_pool_force_close_total 2850
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 320
telemt_me_draining_writers_reap_progress_total 26912
telemt_me_writer_removed_unexpected_total 645
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2339
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25147
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2656
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 194
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24062
telemt_me_writer_teardown_success_total{mode="normal"} 27486
telemt_me_writer_teardown_noop_total 26917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54403
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.859856
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54403
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 320
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 592
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 4139401
telemt_user_connections_current{user="hello"} 3160
telemt_user_octets_from_client{user="hello"} 124780287089 (116.21 GB)
telemt_user_octets_to_client{user="hello"} 1890811885007 (1.72 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1262
telemt_user_unique_ips_recent_window{user="hello"} 387
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 85923.9 (23h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5464621
telemt_connections_bad_total 496100
telemt_connections_current 3200
telemt_connections_me_current 3200
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 165941
telemt_upstream_connect_attempt_total 41397
telemt_upstream_connect_success_total 41130
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 41265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1037
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1716
telemt_me_reconnect_success_total 751
telemt_me_reader_eof_total 695
telemt_me_idle_close_by_peer_total 695
telemt_me_route_drop_no_conn_total 1973890
telemt_me_route_drop_channel_closed_total 94
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4128246
telemt_me_endpoint_quarantine_total 578
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 640
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 19460
telemt_desync_full_logged_total 6359
telemt_desync_suppressed_total 13101
telemt_desync_frames_bucket_total{bucket="1_2"} 4838
telemt_desync_frames_bucket_total{bucket="3_10"} 7376
telemt_desync_frames_bucket_total{bucket="gt_10"} 7246
telemt_pool_swap_total 92
telemt_pool_force_close_total 2714
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 333
telemt_me_draining_writers_reap_progress_total 28327
telemt_me_writer_removed_unexpected_total 665
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2419
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26594
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2502
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 212
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25613
telemt_me_writer_teardown_success_total{mode="normal"} 29013
telemt_me_writer_teardown_noop_total 28337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57350
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.115107
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57350
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 333
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 647
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 4130435
telemt_user_connections_current{user="hello"} 3200
telemt_user_octets_from_client{user="hello"} 120646712227 (112.36 GB)
telemt_user_octets_to_client{user="hello"} 1882346501439 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1264
telemt_user_unique_ips_recent_window{user="hello"} 422
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 85963.1 (23h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18966414
telemt_connections_bad_total 1218442
telemt_connections_current 4017
telemt_connections_me_current 4017
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 529556
telemt_upstream_connect_attempt_total 174511
telemt_upstream_connect_success_total 157625
telemt_upstream_connect_fail_total 15499
telemt_upstream_connect_attempts_per_request{bucket="1"} 173124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8823
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15499
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59398
telemt_me_reconnect_success_total 1767
telemt_me_reader_eof_total 1190
telemt_me_idle_close_by_peer_total 1189
telemt_me_route_drop_no_conn_total 38828475
telemt_me_route_drop_channel_closed_total 112
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15614124
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 636
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 220
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 220
telemt_me_single_endpoint_shadow_rotate_total 668
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_desync_total 29060
telemt_desync_full_logged_total 8573
telemt_desync_suppressed_total 20487
telemt_desync_frames_bucket_total{bucket="1_2"} 6324
telemt_desync_frames_bucket_total{bucket="3_10"} 12889
telemt_desync_frames_bucket_total{bucket="gt_10"} 9847
telemt_pool_swap_total 88
telemt_pool_force_close_total 2942
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 665
telemt_me_draining_writers_reap_progress_total 26495
telemt_me_writer_removed_unexpected_total 1657
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3536
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24358
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2485
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 457
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23553
telemt_me_writer_teardown_success_total{mode="normal"} 27894
telemt_me_writer_teardown_noop_total 26518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54412
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 202.452727
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54412
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 665
telemt_me_refill_failed_total 3519
telemt_me_writer_restored_same_endpoint_total 1224
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 11365
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 15733450
telemt_user_connections_current{user="hello"} 4017
telemt_user_octets_from_client{user="hello"} 147796339563 (137.65 GB)
telemt_user_octets_to_client{user="hello"} 960274348547 (894.33 GB)
telemt_user_msgs_from_client{user="hello"} 352315
telemt_user_msgs_to_client{user="hello"} 633668
telemt_user_unique_ips_current{user="hello"} 1603
telemt_user_unique_ips_recent_window{user="hello"} 744
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 85930.5 (23h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5373307
telemt_connections_bad_total 518825
telemt_connections_current 3046
telemt_connections_me_current 3046
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 111109
telemt_upstream_connect_attempt_total 44522
telemt_upstream_connect_success_total 44038
telemt_upstream_connect_fail_total 400
telemt_upstream_connect_attempts_per_request{bucket="1"} 44438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 400
telemt_me_reconnect_attempts_total 11061
telemt_me_reconnect_success_total 1262
telemt_me_reader_eof_total 1193
telemt_me_idle_close_by_peer_total 1193
telemt_me_route_drop_no_conn_total 2249525
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4169874
telemt_me_endpoint_quarantine_total 528
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 640
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
telemt_me_writers_active_current 44
telemt_desync_total 20636
telemt_desync_full_logged_total 7167
telemt_desync_suppressed_total 13469
telemt_desync_frames_bucket_total{bucket="1_2"} 3950
telemt_desync_frames_bucket_total{bucket="3_10"} 8058
telemt_desync_frames_bucket_total{bucket="gt_10"} 8628
telemt_pool_swap_total 87
telemt_pool_force_close_total 2575
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 316
telemt_me_draining_writers_reap_progress_total 29148
telemt_me_writer_removed_unexpected_total 1173
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2969
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27365
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2215
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26573
telemt_me_writer_teardown_success_total{mode="normal"} 30334
telemt_me_writer_teardown_noop_total 29149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59483
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.274513
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59483
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 316
telemt_me_refill_failed_total 591
telemt_me_writer_restored_same_endpoint_total 1068
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 1512
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4159839
telemt_user_connections_current{user="hello"} 3046
telemt_user_octets_from_client{user="hello"} 110547625593 (102.96 GB)
telemt_user_octets_to_client{user="hello"} 1683026233347 (1.53 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1292
telemt_user_unique_ips_recent_window{user="hello"} 345
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 22766.2 (6h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3057679
telemt_connections_bad_total 114085
telemt_connections_current 2755
telemt_connections_me_current 2755
telemt_handshake_timeouts_total 1318171
telemt_upstream_connect_attempt_total 7413
telemt_upstream_connect_success_total 7311
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 7407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4015
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_reconnect_attempts_total 2196
telemt_me_reconnect_success_total 255
telemt_me_reader_eof_total 197
telemt_me_idle_close_by_peer_total 197
telemt_me_route_drop_no_conn_total 895108
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1448769
telemt_me_endpoint_quarantine_total 119
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 171
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 7961
telemt_desync_full_logged_total 2627
telemt_desync_suppressed_total 5334
telemt_desync_frames_bucket_total{bucket="1_2"} 1428
telemt_desync_frames_bucket_total{bucket="3_10"} 2998
telemt_desync_frames_bucket_total{bucket="gt_10"} 3535
telemt_pool_swap_total 24
telemt_pool_force_close_total 784
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 6455
telemt_me_writer_removed_unexpected_total 215
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 621
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6056
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 679
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 105
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5671
telemt_me_writer_teardown_success_total{mode="normal"} 6677
telemt_me_writer_teardown_noop_total 6455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13132
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.046284
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13132
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 207
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1444565
telemt_user_connections_current{user="hello"} 2755
telemt_user_octets_from_client{user="hello"} 43751444648 (40.75 GB)
telemt_user_octets_to_client{user="hello"} 593762210764 (552.98 GB)
telemt_user_unique_ips_current{user="hello"} 1132
telemt_user_unique_ips_recent_window{user="hello"} 391
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 3737.6 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39740
telemt_connections_bad_total 138
telemt_connections_current 678
telemt_connections_me_current 678
telemt_handshake_timeouts_total 753
telemt_upstream_connect_attempt_total 1655
telemt_upstream_connect_success_total 1649
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 48
telemt_me_reconnect_success_total 18
telemt_me_reader_eof_total 18
telemt_me_idle_close_by_peer_total 18
telemt_me_route_drop_no_conn_total 12271
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37105
telemt_me_endpoint_quarantine_total 23
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 254
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 179
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 4
telemt_pool_force_close_total 87
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 1395
telemt_me_writer_removed_unexpected_total 18
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 91
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1322
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1308
telemt_me_writer_teardown_success_total{mode="normal"} 1413
telemt_me_writer_teardown_noop_total 1395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2808
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.198154
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2808
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 15
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 37051
telemt_user_connections_current{user="hello"} 678
telemt_user_octets_from_client{user="hello"} 966947388 (922.15 MB)
telemt_user_octets_to_client{user="hello"} 31222121104 (29.08 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 85935.5 (23h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6377832
telemt_connections_bad_total 656360
telemt_connections_current 3605
telemt_connections_me_current 3605
telemt_handshake_timeouts_total 185045
telemt_upstream_connect_attempt_total 32619
telemt_upstream_connect_success_total 32488
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 32582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16380
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_reconnect_attempts_total 1391
telemt_me_reconnect_success_total 697
telemt_me_reader_eof_total 673
telemt_me_idle_close_by_peer_total 673
telemt_me_route_drop_no_conn_total 1972489
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 21
telemt_me_route_drop_queue_full_profile_total{profile="high"} 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4890875
telemt_me_endpoint_quarantine_total 572
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 653
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
telemt_me_writers_active_current 43
telemt_desync_total 18541
telemt_desync_full_logged_total 6163
telemt_desync_suppressed_total 12378
telemt_desync_frames_bucket_total{bucket="1_2"} 4524
telemt_desync_frames_bucket_total{bucket="3_10"} 6775
telemt_desync_frames_bucket_total{bucket="gt_10"} 7242
telemt_pool_swap_total 95
telemt_pool_force_close_total 2592
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 327
telemt_me_draining_writers_reap_progress_total 29293
telemt_me_writer_removed_unexpected_total 656
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2385
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27571
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2512
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26701
telemt_me_writer_teardown_success_total{mode="normal"} 29956
telemt_me_writer_teardown_noop_total 29295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59251
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.619196
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59251
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 327
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4866887
telemt_user_connections_current{user="hello"} 3605
telemt_user_octets_from_client{user="hello"} 96878656492 (90.23 GB)
telemt_user_octets_to_client{user="hello"} 2261166905748 (2.06 TB)
telemt_user_unique_ips_current{user="hello"} 1309
telemt_user_unique_ips_recent_window{user="hello"} 436
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 85931.7 (23h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5400466
telemt_connections_bad_total 504309
telemt_connections_current 3563
telemt_connections_me_current 3563
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 154795
telemt_upstream_connect_attempt_total 49046
telemt_upstream_connect_success_total 48684
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 48987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_reconnect_attempts_total 4477
telemt_me_reconnect_success_total 987
telemt_me_reader_eof_total 874
telemt_me_idle_close_by_peer_total 874
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 2026237
telemt_me_route_drop_channel_closed_total 186
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4258732
telemt_me_endpoint_quarantine_total 683
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 655
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
telemt_me_writers_active_current 45
telemt_desync_total 17276
telemt_desync_full_logged_total 5819
telemt_desync_suppressed_total 11457
telemt_desync_frames_bucket_total{bucket="1_2"} 4279
telemt_desync_frames_bucket_total{bucket="3_10"} 6351
telemt_desync_frames_bucket_total{bucket="gt_10"} 6646
telemt_pool_swap_total 93
telemt_pool_force_close_total 2520
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 325
telemt_me_draining_writers_reap_progress_total 28540
telemt_me_writer_removed_unexpected_total 886
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2860
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26605
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2327
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 193
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26020
telemt_me_writer_teardown_success_total{mode="normal"} 29465
telemt_me_writer_teardown_noop_total 28542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58007
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.706387
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58007
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 325
telemt_me_refill_failed_total 199
telemt_me_writer_restored_same_endpoint_total 761
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 4263267
telemt_user_connections_current{user="hello"} 3563
telemt_user_octets_from_client{user="hello"} 81428048845 (75.84 GB)
telemt_user_octets_to_client{user="hello"} 1781592954144 (1.62 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1342
telemt_user_unique_ips_recent_window{user="hello"} 432
```