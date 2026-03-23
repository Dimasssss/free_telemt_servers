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

# Server Metrics 2026-03-23 03:53:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 110839.8 (30h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3779791
telemt_connections_bad_total 369002
telemt_connections_current 1046
telemt_connections_me_current 1046
telemt_handshake_timeouts_total 124772
telemt_upstream_connect_attempt_total 41349
telemt_upstream_connect_success_total 41348
telemt_upstream_connect_attempts_per_request{bucket="1"} 41348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26819
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1442
telemt_me_reconnect_success_total 641
telemt_me_reader_eof_total 658
telemt_me_idle_close_by_peer_total 658
telemt_me_route_drop_no_conn_total 3022609
telemt_me_route_drop_channel_closed_total 1240
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3081130
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 791
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 865
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
telemt_desync_total 13186
telemt_desync_full_logged_total 4193
telemt_desync_suppressed_total 8993
telemt_desync_frames_bucket_total{bucket="1_2"} 3483
telemt_desync_frames_bucket_total{bucket="3_10"} 4828
telemt_desync_frames_bucket_total{bucket="gt_10"} 4875
telemt_pool_swap_total 123
telemt_pool_force_close_total 3715
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 679
telemt_me_draining_writers_reap_progress_total 37854
telemt_me_writer_removed_unexpected_total 635
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2704
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35433
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3659
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34139
telemt_me_writer_teardown_success_total{mode="normal"} 38137
telemt_me_writer_teardown_noop_total 37865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76002
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 380.570332
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76002
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 679
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 575
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 3069972
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 43483648728 (40.50 GB)
telemt_user_octets_to_client{user="hello"} 835996043172 (778.58 GB)
telemt_user_unique_ips_current{user="hello"} 510
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 124206.2 (34h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4071872
telemt_connections_bad_total 380231
telemt_connections_current 583
telemt_connections_me_current 583
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 102622
telemt_upstream_connect_attempt_total 77905
telemt_upstream_connect_success_total 76978
telemt_upstream_connect_fail_total 819
telemt_upstream_connect_attempts_per_request{bucket="1"} 77797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33892
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 819
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10548
telemt_me_reconnect_success_total 3760
telemt_me_reader_eof_total 3743
telemt_me_idle_close_by_peer_total 3743
telemt_me_route_drop_no_conn_total 3651179
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3231110
telemt_me_endpoint_quarantine_total 1003
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 975
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 13210
telemt_desync_full_logged_total 7430
telemt_desync_suppressed_total 5780
telemt_desync_frames_bucket_total{bucket="1_2"} 3001
telemt_desync_frames_bucket_total{bucket="3_10"} 5185
telemt_desync_frames_bucket_total{bucket="gt_10"} 5024
telemt_pool_swap_total 117
telemt_pool_force_close_total 3246
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 257
telemt_me_draining_writers_reap_progress_total 51717
telemt_me_writer_removed_unexpected_total 3666
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6590
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48833
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2788
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48471
telemt_me_writer_teardown_success_total{mode="normal"} 55423
telemt_me_writer_teardown_noop_total 51718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107141
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.717218
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107141
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 257
telemt_me_refill_failed_total 266
telemt_me_writer_restored_same_endpoint_total 3332
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 303
telemt_user_connections_total{user="hello"} 3245590
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 43650765419 (40.65 GB)
telemt_user_octets_to_client{user="hello"} 809734985429 (754.12 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 199066.2 (55h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16489848
telemt_connections_bad_total 1671135
telemt_connections_current 1302
telemt_connections_me_current 1302
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 401474
telemt_upstream_connect_attempt_total 89735
telemt_upstream_connect_success_total 89628
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 89645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44177
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1727
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3099
telemt_me_reconnect_success_total 1640
telemt_me_reader_eof_total 1594
telemt_me_idle_close_by_peer_total 1592
telemt_me_route_drop_no_conn_total 14072122
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13093544
telemt_me_endpoint_quarantine_total 1344
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1504
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
telemt_me_writers_active_current 43
telemt_desync_total 54424
telemt_desync_full_logged_total 17355
telemt_desync_suppressed_total 37069
telemt_desync_frames_bucket_total{bucket="1_2"} 12127
telemt_desync_frames_bucket_total{bucket="3_10"} 21270
telemt_desync_frames_bucket_total{bucket="gt_10"} 21027
telemt_pool_swap_total 216
telemt_pool_force_close_total 6945
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1078
telemt_me_draining_writers_reap_progress_total 68748
telemt_me_writer_removed_unexpected_total 1530
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5774
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63787
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6475
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61803
telemt_me_writer_teardown_success_total{mode="normal"} 69561
telemt_me_writer_teardown_noop_total 68801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138362
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.098898
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138362
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1078
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1422
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 13093530
telemt_user_connections_current{user="hello"} 1302
telemt_user_octets_from_client{user="hello"} 198455650777 (184.83 GB)
telemt_user_octets_to_client{user="hello"} 3538182973147 (3.22 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 199067.5 (55h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12036895
telemt_connections_bad_total 1269766
telemt_connections_current 796
telemt_connections_me_current 796
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 346654
telemt_upstream_connect_attempt_total 103995
telemt_upstream_connect_success_total 102652
telemt_upstream_connect_fail_total 890
telemt_upstream_connect_attempts_per_request{bucket="1"} 103542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3804
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 890
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4560
telemt_me_reconnect_success_total 1958
telemt_me_reader_eof_total 1825
telemt_me_idle_close_by_peer_total 1825
telemt_me_route_drop_no_conn_total 4575156
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8908081
telemt_me_endpoint_quarantine_total 1363
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1524
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
telemt_me_writers_active_current 43
telemt_desync_total 39190
telemt_desync_full_logged_total 13200
telemt_desync_suppressed_total 25990
telemt_desync_frames_bucket_total{bucket="1_2"} 9706
telemt_desync_frames_bucket_total{bucket="3_10"} 15062
telemt_desync_frames_bucket_total{bucket="gt_10"} 14422
telemt_pool_swap_total 213
telemt_pool_force_close_total 6289
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 66818
telemt_me_writer_removed_unexpected_total 1852
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5858
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62671
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5777
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60529
telemt_me_writer_teardown_success_total{mode="normal"} 68529
telemt_me_writer_teardown_noop_total 66843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135372
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.575738
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135372
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 1676
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8845769
telemt_user_connections_current{user="hello"} 796
telemt_user_octets_from_client{user="hello"} 218630767100 (203.62 GB)
telemt_user_octets_to_client{user="hello"} 3993494467287 (3.63 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 199031.6 (55h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11175640
telemt_connections_bad_total 1004920
telemt_connections_current 737
telemt_connections_me_current 737
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 347700
telemt_upstream_connect_attempt_total 88503
telemt_upstream_connect_success_total 86933
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 87138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2055
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5837
telemt_me_reconnect_success_total 2443
telemt_me_reader_eof_total 2190
telemt_me_idle_close_by_peer_total 2189
telemt_me_route_drop_no_conn_total 5353037
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8427658
telemt_me_endpoint_quarantine_total 1406
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1482
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 38408
telemt_desync_full_logged_total 12737
telemt_desync_suppressed_total 25671
telemt_desync_frames_bucket_total{bucket="1_2"} 9701
telemt_desync_frames_bucket_total{bucket="3_10"} 14714
telemt_desync_frames_bucket_total{bucket="gt_10"} 13993
telemt_pool_swap_total 209
telemt_pool_force_close_total 6189
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 752
telemt_me_draining_writers_reap_progress_total 67411
telemt_me_writer_removed_unexpected_total 2336
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6607
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63076
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5618
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61222
telemt_me_writer_teardown_success_total{mode="normal"} 69683
telemt_me_writer_teardown_noop_total 67482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137165
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.900414
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137165
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 752
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2126
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 8419546
telemt_user_connections_current{user="hello"} 737
telemt_user_octets_from_client{user="hello"} 193351642703 (180.07 GB)
telemt_user_octets_to_client{user="hello"} 3495498357553 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 69311.7 (19h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11438875
telemt_connections_bad_total 673956
telemt_connections_current 1367
telemt_connections_me_current 1367
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 295392
telemt_upstream_connect_attempt_total 63649
telemt_upstream_connect_success_total 60263
telemt_upstream_connect_fail_total 2199
telemt_upstream_connect_attempts_per_request{bucket="1"} 62462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21637
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2199
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8148
telemt_me_reconnect_success_total 1416
telemt_me_reader_eof_total 905
telemt_me_idle_close_by_peer_total 904
telemt_me_route_drop_no_conn_total 25322448
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9481071
telemt_me_endpoint_quarantine_total 531
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 555
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 16834
telemt_desync_full_logged_total 4637
telemt_desync_suppressed_total 12197
telemt_desync_frames_bucket_total{bucket="1_2"} 3231
telemt_desync_frames_bucket_total{bucket="3_10"} 6869
telemt_desync_frames_bucket_total{bucket="gt_10"} 6734
telemt_pool_swap_total 71
telemt_pool_force_close_total 2236
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 506
telemt_me_draining_writers_reap_progress_total 22795
telemt_me_writer_removed_unexpected_total 1300
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2955
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21090
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1914
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20559
telemt_me_writer_teardown_success_total{mode="normal"} 24045
telemt_me_writer_teardown_noop_total 22814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46859
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.137691
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46859
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 506
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 914
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 9507553
telemt_user_connections_current{user="hello"} 1367
telemt_user_octets_from_client{user="hello"} 88866424678 (82.76 GB)
telemt_user_octets_to_client{user="hello"} 658976801993 (613.72 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 199038.3 (55h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11145323
telemt_connections_bad_total 984516
telemt_connections_current 886
telemt_connections_me_current 886
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 245471
telemt_upstream_connect_attempt_total 117298
telemt_upstream_connect_success_total 116096
telemt_upstream_connect_fail_total 1026
telemt_upstream_connect_attempts_per_request{bucket="1"} 117122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46096
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1026
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73342
telemt_me_reconnect_success_total 3190
telemt_me_reader_eof_total 2894
telemt_me_idle_close_by_peer_total 2891
telemt_me_route_drop_no_conn_total 5286102
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8773624
telemt_me_endpoint_quarantine_total 1357
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1510
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
telemt_me_writers_active_current 40
telemt_desync_total 46732
telemt_desync_full_logged_total 16047
telemt_desync_suppressed_total 30685
telemt_desync_frames_bucket_total{bucket="1_2"} 9496
telemt_desync_frames_bucket_total{bucket="3_10"} 17903
telemt_desync_frames_bucket_total{bucket="gt_10"} 19333
telemt_pool_swap_total 205
telemt_pool_force_close_total 5911
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 71397
telemt_me_writer_removed_unexpected_total 2913
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7155
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67200
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5162
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65486
telemt_me_writer_teardown_success_total{mode="normal"} 74355
telemt_me_writer_teardown_noop_total 71398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 143598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 145017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 145436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 145709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 145743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 145746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 145746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 145749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 145753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 145753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 145753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 145753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 145753
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.331622
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 145753
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 4316
telemt_me_writer_restored_same_endpoint_total 2691
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8776459
telemt_user_connections_current{user="hello"} 886
telemt_user_octets_from_client{user="hello"} 196986691261 (183.46 GB)
telemt_user_octets_to_client{user="hello"} 3355527178128 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 135874.5 (37h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11874696
telemt_connections_bad_total 486970
telemt_connections_current 834
telemt_connections_me_current 834
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4804193
telemt_upstream_connect_attempt_total 66092
telemt_upstream_connect_success_total 65619
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 66079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30705
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 235
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_reconnect_attempts_total 49226
telemt_me_reconnect_success_total 1926
telemt_me_reader_eof_total 1604
telemt_me_idle_close_by_peer_total 1603
telemt_me_route_drop_no_conn_total 4112974
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5704781
telemt_me_endpoint_quarantine_total 933
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1047
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
telemt_desync_total 32043
telemt_desync_full_logged_total 10951
telemt_desync_suppressed_total 21092
telemt_desync_frames_bucket_total{bucket="1_2"} 6404
telemt_desync_frames_bucket_total{bucket="3_10"} 12638
telemt_desync_frames_bucket_total{bucket="gt_10"} 13001
telemt_pool_swap_total 144
telemt_pool_force_close_total 4109
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 387
telemt_me_draining_writers_reap_progress_total 51150
telemt_me_writer_removed_unexpected_total 1647
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4087
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48761
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3665
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47041
telemt_me_writer_teardown_success_total{mode="normal"} 52848
telemt_me_writer_teardown_noop_total 51157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104005
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.763509
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104005
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 387
telemt_me_refill_failed_total 2748
telemt_me_writer_restored_same_endpoint_total 1702
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5696808
telemt_user_connections_current{user="hello"} 834
telemt_user_octets_from_client{user="hello"} 120752422324 (112.46 GB)
telemt_user_octets_to_client{user="hello"} 2218099379998 (2.02 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 374
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 116845.4 (32h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1603829
telemt_connections_bad_total 37068
telemt_connections_current 653
telemt_connections_me_current 653
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32857
telemt_upstream_connect_attempt_total 55263
telemt_upstream_connect_success_total 55091
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 55235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 814
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2407
telemt_me_reconnect_success_total 971
telemt_me_reader_eof_total 965
telemt_me_idle_close_by_peer_total 965
telemt_me_route_drop_no_conn_total 536373
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1425287
telemt_me_endpoint_quarantine_total 988
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 967
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
telemt_me_writers_active_current 43
telemt_desync_total 10018
telemt_desync_full_logged_total 2824
telemt_desync_suppressed_total 7194
telemt_desync_frames_bucket_total{bucket="1_2"} 3158
telemt_desync_frames_bucket_total{bucket="3_10"} 3782
telemt_desync_frames_bucket_total{bucket="gt_10"} 3078
telemt_pool_swap_total 126
telemt_pool_force_close_total 3174
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 47067
telemt_me_writer_removed_unexpected_total 929
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3550
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44489
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3086
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43893
telemt_me_writer_teardown_success_total{mode="normal"} 48039
telemt_me_writer_teardown_noop_total 47071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95110
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.516954
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95110
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 829
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1420968
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 26769140901 (24.93 GB)
telemt_user_octets_to_client{user="hello"} 595941804387 (555.01 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 199042.7 (55h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13443410
telemt_connections_bad_total 1627616
telemt_connections_current 993
telemt_connections_me_current 993
telemt_handshake_timeouts_total 392450
telemt_upstream_connect_attempt_total 79973
telemt_upstream_connect_success_total 79616
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 79837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3100
telemt_me_reconnect_success_total 1573
telemt_me_reader_eof_total 1560
telemt_me_idle_close_by_peer_total 1560
telemt_me_route_drop_no_conn_total 4499554
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10127561
telemt_me_endpoint_quarantine_total 1464
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1510
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 42515
telemt_desync_full_logged_total 13883
telemt_desync_suppressed_total 28632
telemt_desync_frames_bucket_total{bucket="1_2"} 10351
telemt_desync_frames_bucket_total{bucket="3_10"} 15621
telemt_desync_frames_bucket_total{bucket="gt_10"} 16543
telemt_pool_swap_total 221
telemt_pool_force_close_total 5767
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 72374
telemt_me_writer_removed_unexpected_total 1494
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5590
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68334
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5593
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66607
telemt_me_writer_teardown_success_total{mode="normal"} 73924
telemt_me_writer_teardown_noop_total 72376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 143679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 145408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 145791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 146167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 146287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 146300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 146300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 146300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 146300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 146300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 146300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 146300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 146300
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.887863
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 146300
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1386
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10094171
telemt_user_connections_current{user="hello"} 993
telemt_user_octets_from_client{user="hello"} 195628493220 (182.19 GB)
telemt_user_octets_to_client{user="hello"} 4491414345268 (4.08 TB)
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 199039.4 (55h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11759436
telemt_connections_bad_total 1379217
telemt_connections_current 894
telemt_connections_me_current 894
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 315397
telemt_upstream_connect_attempt_total 107712
telemt_upstream_connect_success_total 106784
telemt_upstream_connect_fail_total 720
telemt_upstream_connect_attempts_per_request{bucket="1"} 107504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2070
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 720
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10899
telemt_me_reconnect_success_total 2691
telemt_me_reader_eof_total 2498
telemt_me_idle_close_by_peer_total 2497
telemt_me_seq_mismatch_total 104
telemt_me_route_drop_no_conn_total 5667954
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9045848
telemt_me_endpoint_quarantine_total 1640
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1514
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
telemt_desync_total 42139
telemt_desync_full_logged_total 13571
telemt_desync_suppressed_total 28568
telemt_desync_frames_bucket_total{bucket="1_2"} 10949
telemt_desync_frames_bucket_total{bucket="3_10"} 15483
telemt_desync_frames_bucket_total{bucket="gt_10"} 15707
telemt_pool_swap_total 211
telemt_pool_force_close_total 5531
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 676
telemt_me_draining_writers_reap_progress_total 72638
telemt_me_writer_removed_unexpected_total 2534
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6967
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68302
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5060
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67107
telemt_me_writer_teardown_success_total{mode="normal"} 75269
telemt_me_writer_teardown_noop_total 72643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 145206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 147004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 147543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 147862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 147912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 147912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 147912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 147912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 147912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 147912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 147912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 147912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 147912
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.598744
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 147912
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 676
telemt_me_refill_failed_total 426
telemt_me_writer_restored_same_endpoint_total 2149
telemt_me_writer_restored_fallback_total 140
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 9050392
telemt_user_connections_current{user="hello"} 894
telemt_user_octets_from_client{user="hello"} 158251446760 (147.38 GB)
telemt_user_octets_to_client{user="hello"} 3534030684486 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 135
```