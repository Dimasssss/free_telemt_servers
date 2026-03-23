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

# Server Metrics 2026-03-23 02:32:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 105957.3 (29h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3634407
telemt_connections_bad_total 341119
telemt_connections_current 946
telemt_connections_me_current 946
telemt_handshake_timeouts_total 115699
telemt_upstream_connect_attempt_total 39474
telemt_upstream_connect_success_total 39473
telemt_upstream_connect_attempts_per_request{bucket="1"} 39473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25590
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1415
telemt_me_reconnect_success_total 618
telemt_me_reader_eof_total 635
telemt_me_idle_close_by_peer_total 635
telemt_me_route_drop_no_conn_total 3000027
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2979017
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 750
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 827
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
telemt_me_writers_active_current 43
telemt_desync_total 12839
telemt_desync_full_logged_total 4057
telemt_desync_suppressed_total 8782
telemt_desync_frames_bucket_total{bucket="1_2"} 3417
telemt_desync_frames_bucket_total{bucket="3_10"} 4685
telemt_desync_frames_bucket_total{bucket="gt_10"} 4737
telemt_pool_swap_total 117
telemt_pool_force_close_total 3584
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 669
telemt_me_draining_writers_reap_progress_total 36168
telemt_me_writer_removed_unexpected_total 612
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2572
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33857
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3528
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32584
telemt_me_writer_teardown_success_total{mode="normal"} 36429
telemt_me_writer_teardown_noop_total 36179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72608
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.266060
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72608
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 669
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 553
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 2967975
telemt_user_connections_current{user="hello"} 946
telemt_user_octets_from_client{user="hello"} 42400670668 (39.49 GB)
telemt_user_octets_to_client{user="hello"} 811612034364 (755.87 GB)
telemt_user_unique_ips_current{user="hello"} 446
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 119323.6 (33h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4026124
telemt_connections_bad_total 372277
telemt_connections_current 252
telemt_connections_me_current 252
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101251
telemt_upstream_connect_attempt_total 74244
telemt_upstream_connect_success_total 73335
telemt_upstream_connect_fail_total 802
telemt_upstream_connect_attempts_per_request{bucket="1"} 74137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 802
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10399
telemt_me_reconnect_success_total 3707
telemt_me_reader_eof_total 3690
telemt_me_idle_close_by_peer_total 3690
telemt_me_route_drop_no_conn_total 3644402
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3197987
telemt_me_endpoint_quarantine_total 965
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 936
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
telemt_me_writers_active_current 44
telemt_desync_total 13038
telemt_desync_full_logged_total 7322
telemt_desync_suppressed_total 5716
telemt_desync_frames_bucket_total{bucket="1_2"} 2960
telemt_desync_frames_bucket_total{bucket="3_10"} 5119
telemt_desync_frames_bucket_total{bucket="gt_10"} 4959
telemt_pool_swap_total 112
telemt_pool_force_close_total 3158
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 49438
telemt_me_writer_removed_unexpected_total 3619
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6419
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46672
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2700
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46280
telemt_me_writer_teardown_success_total{mode="normal"} 53091
telemt_me_writer_teardown_noop_total 49439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102530
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.657499
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102530
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 3289
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 3211350
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 43283710126 (40.31 GB)
telemt_user_octets_to_client{user="hello"} 797158441042 (742.41 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 194183.4 (53h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16403459
telemt_connections_bad_total 1663399
telemt_connections_current 964
telemt_connections_me_current 964
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 398683
telemt_upstream_connect_attempt_total 87346
telemt_upstream_connect_success_total 87240
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 87257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42832
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1723
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3044
telemt_me_reconnect_success_total 1620
telemt_me_reader_eof_total 1567
telemt_me_idle_close_by_peer_total 1565
telemt_me_route_drop_no_conn_total 14055059
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13023851
telemt_me_endpoint_quarantine_total 1301
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1463
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
telemt_desync_total 54039
telemt_desync_full_logged_total 17200
telemt_desync_suppressed_total 36839
telemt_desync_frames_bucket_total{bucket="1_2"} 12059
telemt_desync_frames_bucket_total{bucket="3_10"} 21105
telemt_desync_frames_bucket_total{bucket="gt_10"} 20875
telemt_pool_swap_total 210
telemt_pool_force_close_total 6834
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1067
telemt_me_draining_writers_reap_progress_total 66549
telemt_me_writer_removed_unexpected_total 1507
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5626
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61709
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6364
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59715
telemt_me_writer_teardown_success_total{mode="normal"} 67335
telemt_me_writer_teardown_noop_total 66602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133937
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.914255
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133937
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1067
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1402
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 13023840
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 197552643761 (183.99 GB)
telemt_user_octets_to_client{user="hello"} 3507867891295 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 459
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 194184.8 (53h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11950172
telemt_connections_bad_total 1250463
telemt_connections_current 671
telemt_connections_me_current 671
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 345150
telemt_upstream_connect_attempt_total 101681
telemt_upstream_connect_success_total 100349
telemt_upstream_connect_fail_total 879
telemt_upstream_connect_attempts_per_request{bucket="1"} 101228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 879
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4473
telemt_me_reconnect_success_total 1923
telemt_me_reader_eof_total 1789
telemt_me_idle_close_by_peer_total 1789
telemt_me_route_drop_no_conn_total 4563443
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8857383
telemt_me_endpoint_quarantine_total 1316
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1484
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 39045
telemt_desync_full_logged_total 13149
telemt_desync_suppressed_total 25896
telemt_desync_frames_bucket_total{bucket="1_2"} 9674
telemt_desync_frames_bucket_total{bucket="3_10"} 14994
telemt_desync_frames_bucket_total{bucket="gt_10"} 14377
telemt_pool_swap_total 207
telemt_pool_force_close_total 6186
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 713
telemt_me_draining_writers_reap_progress_total 64729
telemt_me_writer_removed_unexpected_total 1816
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5724
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60680
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5674
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58543
telemt_me_writer_teardown_success_total{mode="normal"} 66404
telemt_me_writer_teardown_noop_total 64754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131158
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.528239
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131158
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 713
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1646
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 8795107
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 218133301256 (203.15 GB)
telemt_user_octets_to_client{user="hello"} 3975317765755 (3.62 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 194148.9 (53h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11101433
telemt_connections_bad_total 985620
telemt_connections_current 484
telemt_connections_me_current 484
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345984
telemt_upstream_connect_attempt_total 86021
telemt_upstream_connect_success_total 84460
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 84665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41215
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5788
telemt_me_reconnect_success_total 2410
telemt_me_reader_eof_total 2155
telemt_me_idle_close_by_peer_total 2154
telemt_me_route_drop_no_conn_total 5343483
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8387483
telemt_me_endpoint_quarantine_total 1365
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1444
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 48
telemt_desync_total 38258
telemt_desync_full_logged_total 12679
telemt_desync_suppressed_total 25579
telemt_desync_frames_bucket_total{bucket="1_2"} 9666
telemt_desync_frames_bucket_total{bucket="3_10"} 14648
telemt_desync_frames_bucket_total{bucket="gt_10"} 13944
telemt_pool_swap_total 203
telemt_pool_force_close_total 6082
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 746
telemt_me_draining_writers_reap_progress_total 65177
telemt_me_writer_removed_unexpected_total 2303
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6468
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60946
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5511
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59095
telemt_me_writer_teardown_success_total{mode="normal"} 67414
telemt_me_writer_teardown_noop_total 65248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132662
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.851957
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132662
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 746
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2097
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 8379405
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 193010636243 (179.76 GB)
telemt_user_octets_to_client{user="hello"} 3481006008589 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 64428.9 (17h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11326754
telemt_connections_bad_total 670105
telemt_connections_current 1133
telemt_connections_me_current 1133
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 283900
telemt_upstream_connect_attempt_total 60470
telemt_upstream_connect_success_total 57329
telemt_upstream_connect_fail_total 2052
telemt_upstream_connect_attempts_per_request{bucket="1"} 59381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20332
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6019
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2052
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7857
telemt_me_reconnect_success_total 1325
telemt_me_reader_eof_total 859
telemt_me_idle_close_by_peer_total 858
telemt_me_route_drop_no_conn_total 25302114
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9392639
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 515
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_me_writers_active_current 87
telemt_desync_total 16489
telemt_desync_full_logged_total 4523
telemt_desync_suppressed_total 11966
telemt_desync_frames_bucket_total{bucket="1_2"} 3140
telemt_desync_frames_bucket_total{bucket="3_10"} 6725
telemt_desync_frames_bucket_total{bucket="gt_10"} 6624
telemt_pool_swap_total 66
telemt_pool_force_close_total 2110
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 491
telemt_me_draining_writers_reap_progress_total 20781
telemt_me_writer_removed_unexpected_total 1213
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2742
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19198
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1803
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18671
telemt_me_writer_teardown_success_total{mode="normal"} 21940
telemt_me_writer_teardown_noop_total 20800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42740
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.976019
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42740
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 491
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 870
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 9418496
telemt_user_connections_current{user="hello"} 1133
telemt_user_octets_from_client{user="hello"} 87721208034 (81.70 GB)
telemt_user_octets_to_client{user="hello"} 627749280222 (584.64 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 194155.4 (53h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11060374
telemt_connections_bad_total 965932
telemt_connections_current 841
telemt_connections_me_current 841
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 243972
telemt_upstream_connect_attempt_total 114842
telemt_upstream_connect_success_total 113661
telemt_upstream_connect_fail_total 1005
telemt_upstream_connect_attempts_per_request{bucket="1"} 114666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44711
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1005
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73144
telemt_me_reconnect_success_total 3143
telemt_me_reader_eof_total 2840
telemt_me_idle_close_by_peer_total 2838
telemt_me_route_drop_no_conn_total 5270766
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8715609
telemt_me_endpoint_quarantine_total 1317
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1471
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
telemt_me_writers_active_current 45
telemt_desync_total 46433
telemt_desync_full_logged_total 15929
telemt_desync_suppressed_total 30504
telemt_desync_frames_bucket_total{bucket="1_2"} 9440
telemt_desync_frames_bucket_total{bucket="3_10"} 17773
telemt_desync_frames_bucket_total{bucket="gt_10"} 19220
telemt_pool_swap_total 199
telemt_pool_force_close_total 5792
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 668
telemt_me_draining_writers_reap_progress_total 69197
telemt_me_writer_removed_unexpected_total 2860
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7017
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65084
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5043
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63405
telemt_me_writer_teardown_success_total{mode="normal"} 72101
telemt_me_writer_teardown_noop_total 69198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 139145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 140563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141299
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.303129
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141299
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 668
telemt_me_refill_failed_total 4308
telemt_me_writer_restored_same_endpoint_total 2648
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 8718538
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 196286446365 (182.81 GB)
telemt_user_octets_to_client{user="hello"} 3331635383168 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 130991.6 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11765538
telemt_connections_bad_total 483212
telemt_connections_current 619
telemt_connections_me_current 619
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4771107
telemt_upstream_connect_attempt_total 63477
telemt_upstream_connect_success_total 63016
telemt_upstream_connect_fail_total 449
telemt_upstream_connect_attempts_per_request{bucket="1"} 63465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 449
telemt_me_reconnect_attempts_total 49110
telemt_me_reconnect_success_total 1875
telemt_me_reader_eof_total 1552
telemt_me_idle_close_by_peer_total 1551
telemt_me_route_drop_no_conn_total 4100218
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5654267
telemt_me_endpoint_quarantine_total 898
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1009
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31819
telemt_desync_full_logged_total 10870
telemt_desync_suppressed_total 20949
telemt_desync_frames_bucket_total{bucket="1_2"} 6346
telemt_desync_frames_bucket_total{bucket="3_10"} 12559
telemt_desync_frames_bucket_total{bucket="gt_10"} 12914
telemt_pool_swap_total 139
telemt_pool_force_close_total 4000
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 380
telemt_me_draining_writers_reap_progress_total 48768
telemt_me_writer_removed_unexpected_total 1597
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3933
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46481
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3559
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44768
telemt_me_writer_teardown_success_total{mode="normal"} 50414
telemt_me_writer_teardown_noop_total 48775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99189
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.724873
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99189
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 380
telemt_me_refill_failed_total 2744
telemt_me_writer_restored_same_endpoint_total 1659
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5646385
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 120191793724 (111.94 GB)
telemt_user_octets_to_client{user="hello"} 2193349111534 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 111962.7 (31h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1556300
telemt_connections_bad_total 36865
telemt_connections_current 445
telemt_connections_me_current 445
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31972
telemt_upstream_connect_attempt_total 53030
telemt_upstream_connect_success_total 52864
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 53002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 799
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2319
telemt_me_reconnect_success_total 949
telemt_me_reader_eof_total 939
telemt_me_idle_close_by_peer_total 939
telemt_me_route_drop_no_conn_total 524815
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1383479
telemt_me_endpoint_quarantine_total 944
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 929
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 9566
telemt_desync_full_logged_total 2732
telemt_desync_suppressed_total 6834
telemt_desync_frames_bucket_total{bucket="1_2"} 2881
telemt_desync_frames_bucket_total{bucket="3_10"} 3622
telemt_desync_frames_bucket_total{bucket="gt_10"} 3063
telemt_pool_swap_total 121
telemt_pool_force_close_total 3062
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 45018
telemt_me_writer_removed_unexpected_total 904
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3427
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42537
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2974
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41956
telemt_me_writer_teardown_success_total{mode="normal"} 45964
telemt_me_writer_teardown_noop_total 45022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90986
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.409267
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90986
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 809
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1379241
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 26308267517 (24.50 GB)
telemt_user_octets_to_client{user="hello"} 584065535475 (543.95 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 194160.1 (53h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13384083
telemt_connections_bad_total 1618924
telemt_connections_current 745
telemt_connections_me_current 745
telemt_handshake_timeouts_total 390744
telemt_upstream_connect_attempt_total 77325
telemt_upstream_connect_success_total 76971
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 77189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38884
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3056
telemt_me_reconnect_success_total 1533
telemt_me_reader_eof_total 1519
telemt_me_idle_close_by_peer_total 1519
telemt_me_route_drop_no_conn_total 4488788
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10080389
telemt_me_endpoint_quarantine_total 1414
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1472
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
telemt_me_writers_active_current 44
telemt_desync_total 42280
telemt_desync_full_logged_total 13806
telemt_desync_suppressed_total 28474
telemt_desync_frames_bucket_total{bucket="1_2"} 10281
telemt_desync_frames_bucket_total{bucket="3_10"} 15533
telemt_desync_frames_bucket_total{bucket="gt_10"} 16466
telemt_pool_swap_total 215
telemt_pool_force_close_total 5677
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 683
telemt_me_draining_writers_reap_progress_total 69938
telemt_me_writer_removed_unexpected_total 1454
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5448
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65999
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5503
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64261
telemt_me_writer_teardown_success_total{mode="normal"} 71447
telemt_me_writer_teardown_noop_total 69940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 138768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 140495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141387
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.827884
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141387
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 683
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1346
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10047062
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 195035622636 (181.64 GB)
telemt_user_octets_to_client{user="hello"} 4467377616116 (4.06 TB)
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 194156.5 (53h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11691501
telemt_connections_bad_total 1366669
telemt_connections_current 513
telemt_connections_me_current 513
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 312853
telemt_upstream_connect_attempt_total 104972
telemt_upstream_connect_success_total 104068
telemt_upstream_connect_fail_total 696
telemt_upstream_connect_attempts_per_request{bucket="1"} 104764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44487
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 696
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10673
telemt_me_reconnect_success_total 2637
telemt_me_reader_eof_total 2447
telemt_me_idle_close_by_peer_total 2446
telemt_me_seq_mismatch_total 102
telemt_me_route_drop_no_conn_total 5656036
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8994915
telemt_me_endpoint_quarantine_total 1589
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 1475
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 41963
telemt_desync_full_logged_total 13513
telemt_desync_suppressed_total 28450
telemt_desync_frames_bucket_total{bucket="1_2"} 10855
telemt_desync_frames_bucket_total{bucket="3_10"} 15435
telemt_desync_frames_bucket_total{bucket="gt_10"} 15673
telemt_pool_swap_total 205
telemt_pool_force_close_total 5443
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 671
telemt_me_draining_writers_reap_progress_total 70151
telemt_me_writer_removed_unexpected_total 2488
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6826
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65903
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64708
telemt_me_writer_teardown_success_total{mode="normal"} 72729
telemt_me_writer_teardown_noop_total 70156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 140195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 141977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 142516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142885
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.510346
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142885
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 671
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 2116
telemt_me_writer_restored_fallback_total 137
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 8999473
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 157617618036 (146.79 GB)
telemt_user_octets_to_client{user="hello"} 3506893010222 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 69
```